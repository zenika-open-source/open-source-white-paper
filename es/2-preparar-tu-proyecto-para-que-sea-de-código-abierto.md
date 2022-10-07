# Preparar tu proyecto para que sea de código abierto.

En un [artículo anterior](Link to previous article/Link al artículo anterior), te ayudamos a presentar tu primera contribución. ¿Quieres lanzar  tu propio proyecto de Código Abierto pero no sabes qué hacer antes de permitir que todo el mundo vea tu código? No te preocupes, en este artículo te daremos todos los requisitos previos que necesitas para lanzar tu proyecto.

## Requisitos previos

Si quieres que tu proyecto tenga contribuciones necesitas escribir al menos alguna documentación. Hay cuatro archivos esenciales:

- Readme (o Léeme)
- Licencia
- Guia de contribución
- Código de conducta

A continuación describiremos cada uno de ellos y te guiaremos para que los escribas tú.

## README

El primero es bastante conocido, y probablemente tengas alguno, pero hablemos un poco sobre los README.md.

Mike McQuaid teorizó sobre ["contributor funnel" de Código Abierto](https://mikemcquaid.com/2018/08/14/the-open-source-contributor-funnel-why-people-dont-contribute-to-your-open-source-project/) y cómo conseguir contribuyentes en tus proyectos de Código Abierto. Necesitas proporcionar información para todos los tipos de visitantes (_usuarios_, _contribuyentes_, _mantenedores_) en tu readme.

La descripción de tu proyecto y los primeros párrafos de tu readme deberían ser un resumen simple de tu proyecto y contener todas las palabras clave que la gente va a buscar. -- [Andrey Petrov](https://medium.com/code-zen/how-to-maintain-a-successful-open-source-project-aaa2a5437d3a)

Para empezar, nadie puede leerte la mente. Deberías explicar los objetivos de tu proyecto. No tiene que ser un ensayo, una sola frase es lo suficientemente buena, como en [El readme de Conference Hall’s](https://github.com/bpetetot/conference-hall):

> Conference Hall es una plataforma abierta del tipo Software Como Servicio (SaaS) para administrar Convocatorias A Publicar (CFP) y presentaciones del ponente para tus conferencias y meetups. Como ponente escribes una charla una vez y la presentas en cada evento que quieras, dentro de la plataforma.

Esta sección es lo primero que verá la gente que entre a tu proyecto por primera vez, por eso necesitas llamar su atención.

Otra parte importante a incluir en tu readme es cómo instalar y utilizar tu proyecto. Es esencial para que los _usuarios_ puedan probarlo fácilmente. Gatsby hace un buen trabajo explicando cómo tener una página web [funcionando en 5 minutos](https://github.com/gatsbyjs/gatsby#-get-up-and-running-in-5-minutes) con si CLI

Por último, pero no menos importante, deberías proveer instrucciones para contribuyentes futuros. La mayoría de las veces un link a tu guía de contribución es suficiente.

Para gente que está empezando, una [plantilla](https://www.makeareadme.com/#template-1) se puede encontrar en makereadme.com . Contiene todas las secciones de las que hemos hablado. Allí puedes encontrar más información sobre cómo escribir un buen readme. Es más, puedes usar herramientas para generar tus readmes como [readme-md-generator](https://github.com/kefranabg/readme-md-generator). Llena tu archivo con información extraída de tu configuración de Git (o más específicamente del archivo `package.json` si tu proyecto está hecho con JavaScript). Puedes encontrar otros [generadores de readmes](https://github.com/search?utf8=%E2%9C%93&q=generate+readme&type=Repositories) Para varios idiomas en GitHub.

## Licencia

El archivo LICENCIA es lo que permite que el Código Abierto sea posible. Protege a los _usuarios_ y a los _contribuyentes_ Dándoles derecho de usar, copiar, modificar y contribuir a tu proyecto. Este archivo es obligatorio, por ello deberías considerar no contribuir en proyectos que no tengan una licencia.

[OSI](https://opensource.org/) es un organismo que ha estado promoviendo los softwares y las comunidades de código abierto durante alrededor de 20 años. Tienen un proceso de revisión de licencias. Las licencias aprobadas por el OSI son las mas populares, como la de [MIT](https://opensource.org/licenses/MIT) o la de [Apache 2.0](https://opensource.org/licenses/Apache-2.0). Puedes encontrar una [buena comparación](https://choosealicense.com/licenses/) entre licencias en [choosealicense.com](https://choosealicense.com/).

## Guia de contribución

Un archivo CONTRIBUTING.md, en tu repositorio o web de código abierto, provee a los potenciales contribuyentes de tu proyecto con una guía corta de cómo pueden ayudarte con tu proyecto o grupo de estudio. Por convenio deberías escribir la palabra "contributing" en mayusculas como nombre del archivo, y guardarlo como un recurso en Markdown (de ahí la extensión .md) -- [Mozilla Science Lab](https://mozillascience.github.io/working-open-workshop/contributing/)

Antes hablamos sobre "El 'contributor funnel' de código abierto" en nuestro readme. Dimos documentación para ayudar a los _usuarios_ para instalar y utilizar tu proyecto. Ahora nos centraremos en los _contribuyentes_. La guía de contribución está diseñada para dar instrucciones a cualquiera que quiera participar en tu proyecto.

La mayoría de las contribuciones las hacen los usuarios que encuentran un problema usando tu proyecto. Está bien añadir instrucciones sobre cómo reportar un bug o sugerir nuevas características.

Si quieres que la gente contribuya al código necesitas proveer todos los detalles de cómo configurar el entorno de desarrollo del proyecto y cómo enviar contribuciones. la [guía de contribución de Moncha](https://github.com/mochajs/mocha/blob/master/.github/CONTRIBUTING.md#shoe-contributing-code-step-by-step) es un buen ejemplo de instrucciones dadas paso por paso para fusionar tus contribuciones.

Ll guia de contribución es también el lugar indicado para describir tus estilos de código. Puedes imponer buenas prácticas como testear, o conveciones como en la [guía de contribución de Immutadot](https://github.com/zenika-open-source/immutadot/blob/master/.github/CONTRIBUTING.md#tests-and-code-style-policeman).

Si tu proyecto está en GitHub, este archivo se [enlazará automaticamente](https://help.github.com/en/articles/setting-guidelines-for-repository-contributors) cuando un contribuyente abra una  "issue" o cree una "pull request".

## Código de conducta

Tener un CODE_OF_CONDUCT.md en tus repositorios públicos permite saber por adelantado a los potenciales _contribuyentes_ qué trato esperar por parte de la comunidad y los _mantenedores_. -- [Michael Jolley](https://dev.to/michaeljolley/using-a-contributing-codeofconduct-to-assist-others-in-contributing-to-public-repositories-1l90)

El código de conducta de tu proyecto es un documento que protege a cada participante. Ayuda a crear una comunidad acogedora.

Una buena adición a tu código de conducta es una explicación sobre cómo planeas hacer que se cumpla. Es importante demostrar que te lo tomas en serio para que todos puedan saber qué medidas se tomarán en caso de que lo infrinjan.

Deberías dejar clara también la manera de reportar infracciones, como por email.

El código de conducta más famoso es el ["Contributor Covenant"](https://www.contributor-covenant.org/). Lo usan miles de proyectos de código abierto. Si tu proyecto está en GitHub puedes añadir directamente el "Contributor Covenant" o el ["Citizen Code of Conduct"](http://citizencodeofconduct.org/) mediante tu interfaz de repositorios. Tienes que ir a `Insights > Community > Code of conduct`, haciendo click en el botón de añadir y eligiendo el código de conducta, creará un commit por ti.

Tu proyecto está ahora preparado para ser de código abierto. ¡Puedes empezar a promocionarlo y conseguir tus primeras contribuciones!

¡Si quieres noticias sobre nuestros proyectos o futuros artículos, considera seguirnos en Twitter [@ZenikaOSS](https://twitter.com/ZenikaOSS)!

