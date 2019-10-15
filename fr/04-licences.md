
# Chapitre 4: Licences

Que vous soyez un développeur ou bien un mainteneur de projets Open Source, il est indispensable d'avoir une connaissance des différents types de licences. Quels sont vos droits et devoirs lorsque vous les utilisez. Plusieurs types de licences s’offrent à vous et chacune peut présenter des avantages et des inconvénients qu’il convient de mesurer avant de choisir. Mais il faut rester vigilant. Il peut y avoir des confusions entre les différentes catégories de logiciels « libres » (OSS, freeware, Domaine public…) et il existe des dizaines de licences libres dont certaines sont virales. Cet article a pour but de vous aider à comprendre les différentes caractéristiques des licences et de choisir la plus adaptée à votre projet.

## Logiciel libre & Open Source

La [Free Software Foundation (FSF)](www.fsf.org), société américaine à but non lucratif fondée en 1985 par R. Stallman, soutient le système d’exploitation GNU et gère les licences « GPL ».

Cette fondation donne une définition du logiciel libre basée sur quatre libertés irrévocables:

- Liberté d'utiliser le logiciel.
- Liberté de copier le logiciel (comprend la liberté de vendre des copies).
- Liberté d'étudier le logiciel (suppose l'accès au code source).
- Liberté de modifier le logiciel et de redistribuer les versions modifiées.

Les œuvres sous licence libre ne sont pas toujours disponibles gratuitement et les services associés (développement, garanties, support, etc.) sont souvent payants. Une œuvre contaminée par une licence libre, qui pouvait au départ n’être disponible que contre paiement, doit être rediffusée librement.

> « Think Free as Free speech and not Free beer »
> – R. Stallman

Tandis que l'[Open Source Initiative (OSI)](http://opensource.org/), société américaine à but non lucratif fondée en 1998 par E. Raymond & B. Perens promeut le code Open Source.

Selon l’OSI, pour qu’un logiciel soit Open Source, sa licence doit respecter les 10 critères suivants:

- Redistribution libre.
- Fourniture du code source.
- Permettre les travaux dérivés et modifications.
- Intégrité du code source de l’auteur.
- Pas de discrimination entre les personnes ou les groupes.
- Pas de discrimination entre les domaines d'application.
- Pas de restriction sur la distribution de la licence (vs NDA).
- La licence ne doit pas être spécifique à un produit.
- La licence ne doit pas restreindre d'autres logiciels.
- La licence doit être technologiquement neutre.


> « Les deux termes décrivent pratiquement la même catégorie de logiciel. Mais ils représentent des vues basées sur des valeurs fondamentalement différentes. »
> – R. Stallman

https://twitter.com/OpenSourceOrg/status/1174073039534706688?s=20


## Copyright, copyleft et domaine public

Avant de présenter les différents types de licences disponibles, il est nécessaire de comprendre les différents types de droits appliqués aux œuvres. Voici une explication, en termes simples, des 3 grands domaines d'application des droits.

Le **copyright** (ou droit d'auteur) est un droit accordé à l'auteur de l'œuvre originale, y compris le droit d'autoriser ou d'interdire la publication ou la distribution de son œuvre. Il protège les auteurs de la copie ou de la vente non autorisée de leurs œuvres. Les droits d'auteur sont accordés pour une durée limitée, au terme de laquelle l'œuvre entre dans le domaine public.

Le **domaine public** comprend toutes les créations auxquelles ne s'applique aucun droit de propriété intellectuelle exclusif. Ces droits peuvent être expirés, avoir été confisqués, expressément renoncés ou être inapplicables. Les droits d’auteur sont généralement valables jusqu’à 50 à 100 ans après le décès de l’auteur. En termes simples, tout le monde peut utiliser, modifier et vendre ces créations sans l’autorisation de son auteur.

Par exemple, les compositions de Beethoven sont entré dans le domaine public 70 ans après sa mort en 1827. Ses compositions musicales sont disponibles pour être utilisées et vendues par tous.

Sous **copyleft**, tout le monde peut modifier et distribuer le travail. Cela ne nécessite qu'une condition: la même liberté doit être préservée dans les versions modifiées de l'œuvre originale. Les gens peuvent utiliser, modifier et distribuer le travail comme ils le souhaitent. Toutefois, le copyleft oblige le travail modifié à être distribué sur la base de la même licence. Cependant, il n'est pas nécessaire que le contenu copylefté soit rendu gratuit comme le travail dans le domaine public.

La licence publique générale GNU, écrite à l'origine par Richard Stallman, était la première licence copyleft.

## Quel type de licence choisir ou utiliser

Un logiciel libre a toujours une licence (contrat) d’utilisation associée, il est nécessaire d'analyser les conditions d’utilisation, les droits et les obligations en résultant.

Pour faciliter la compréhension des différents types de licence, nous pouvons les classifier selon le degré de liberté qu'elles accordent à l’utilisateur :

- « Copyleft fort »
- « Copyleft faible »
- « Permissive »

### Copyleft fort

Une licence avec un copyleft fort a **un caractère fortement contaminant**, lorsque le composant X d’un logiciel, est sous une licence très fortement copyleftée, cette même licence  s’impose à l’ensemble du logiciel qui contient ce composant lors de sa diffusion. On parle alors de licence « contaminante » ou « virale ». Elle oblige à distribuer le logiciel libre modifié sous la même licence, à rendre disponible le code source associé et à distribuer l’ensemble du programme (libre et propriétaire) sous la même licence.

**Quelques licences à copyleft fort:**

- GPL: General Public License V3
- AGPL: Affero General Public License
- CC: Creative Commons déclinée en 6 licences, dont certaines permissives

Dans le cas de la licence GPL,il existe quelques cas explicites d’utilisation qui ne déclenchent pas le phénomène de contamination. Soit par des clauses d'exception inscrites dans la licence. Par exemple le [GCC Runtime](https://gcc.gnu.org/onlinedocs/libstdc++/manual/license.html). Soit dans le cas de binaires indépendants, c'est à dire que votre logiciel utilise un programme ayant la license GPL, mais ne le distribue pas. **(METTRE UN EXEMPLE)**

Les threads Stack Overflow sont également sous licence. Lorsque vous copiez-collez un bout de code depuis le forum, il est important de savoir que tous les snippets de code postés sont sous la licence Creative Commons CC. 😱

### Copyleft faible

Une licence avec un copyleft faible a **un caractère faiblement contaminant**, elle oblige à distribuer le logiciel libre modifié sous la même licence et à rendre disponible le code source associé.

**Quelques licences à copyleft faible:**

- LGPL: Lesser GPL
- EPL: Eclipse Public License
- MPL: Mozilla Public License

### Permissive

Les licences permissives offrent **la plus grande liberté avec un partage sans condition**. En général, seule la citation des auteurs originaux est demandée et elles permettent à tout acteur de changer la licence sous laquelle le logiciel est distribué, sans obligation de diffusion.

**Quelques licences permissives:**

- BSD : Berkeley Software Distribution
- MIT : Massachussetts Institute of Technology
- Apache

Il existe également des licences permissives plus esotériques. Comme la Postcard licence, dont la seule obligation est d'envoyer une carte postale à l’auteur. Ou encore la [WTFPL](http://www.wtfpl.net/) (Do What the Fuck You Want to Public License), dont le titre dit tout. 🙂

## Conclusion

En tant que développeur, si vous utilisez des librairies ou logiciels tiers, n'oubliez pas de vérifier leur licence car elle peut impacter celle de votre logiciel. En tant que mainteneur de projets Open Source, choisissez correctement votre licence, que ce soit pour protéger votre œuvre ou son utilisation. Le site web [« Choose a license »]( https://choosealicense.com/) vous permet de bien choisir votre licence en fonction de vos usages.
