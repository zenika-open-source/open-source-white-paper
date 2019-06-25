# Chapitre 1: Getting Started 🥚

Le monde de l'open source est vaste, il est très facile de s'y perdre. Quand on est nouveau dans l'open source, ce monde peut paraître peu accessible et intimidant. Par où commencer ? Y a-t-il des règles et des codes à suivre ? Comment contribuer même si je ne code pas ?
Pas d'inquiétude, dans cet article nous allons te donner tous les codes nécessaires pour bien démarrer, choisir le bon projet et proposer sa première contribution.


## Premiers pas dans l’open source 🐣

Tout d'abord, il faut déterminer sur quel projet tu souhaites démarrer ta première contribution. Comme il existe des millions de projets open source, il peut être difficile de trouver son chemin.

Une première idée, qui est peut-être la plus simple, est **d’identifier des projets que tu aimes, que tu utilises souvent ou qui t'intéressent.** Il sera alors plus évident de démarrer dans un environnement que tu connais et sur lequel tu garderas de la motivation à plus long terme.

Il est également important de prendre en compte la maturité du projet et sa taille. Il est tentant de démarrer sur de gros frameworks, librairies ou outils comme VS Code, MongoDB, Android, React… Ces types de projets ont de nombreux contributeurs et beaucoup de bugs à corriger ou fonctionnalités à réaliser. Les contributions sur ces projets apportent une certaine satisfaction quand elles sont intégrées. Mais ces projets, avec des millions de lignes de code, ne sont pas les meilleurs choix pour débuter dans l'open source. Ils seront plus difficiles à appréhender par leur taille et les workflows qui viennent avec. Leurs communautés sont déjà très développées et beaucoup de personnes proposent des contributions pour un nombre de mainteneurs limités. Il peut alors se passer un certain temps avant que ta contribution ne soit étudiée, puis éventuellement acceptée.

**Démarrer sur des projets plus petits et qui ont du potentiel est un meilleur moyen de débuter.** Pour cela, il suffit de surveiller régulièrement ceux qui montent, par exemple sur le [trending de GitHub](https://github.com/trending/javascript?since=monthly), et de trouver des projets qui te correspondent.

Un autre bon moyen d'identifier un projet sur lequel participer est de **sélectionner ceux qui recherchent activement des contributeurs.** Plusieurs sites et outils permettent d’en trouver :

* [Awesome for beginners](https://github.com/MunGell/awesome-for-beginners)* est une liste de projets à la recherche de contributeurs (débutants ou non) en listant leurs *« Good First Issues »*. De la même manière, le site [Up for grabs](https://up-for-grabs.net) permet de trouver des projets à la recherche de contributeurs.

* [CodeTriage](https://www.codetriage.com/) est un outil permettant de s'abonner à des projets open source et de recevoir de nouvelles demandes de contribution tous les jours.

* [First contributions](https://firstcontributions.github.io/) est un peu différent, c'est un workshop pour réaliser sa première contribution en moins de cinq minutes. Elle présente la base du workflow git pour faire des contributions sur GitHub. En plus de ce tutoriel, le site propose des liens vers les *« Good First Issues »* de gros projets GitHub.

* Les soirées ou événements communautaires comme le [HacktoberFest](https://hacktoberfest.digitalocean.com/) représentent également un bon moyen de démarrer sur des projets à la recherche de contributeur. Par exemple, le [hack.commit.push](https://hack-commit-pu.sh/) propose une journée de développement open source, ouverte à tous, quelque soit votre niveau. En début de journée, des ateliers d'introduction sont présentés pour ensuite enchaîner sur des contributions open source accompagnées de mentor.

Un fois que tu as trouvé le ou les projets de tes rêves, il te faudra commencer par te documenter sur ces projets, par exemple en lisant le README, le code de conduite et le guide de contribution. Ce n'est pas très long, mais nécessaire avant de démarrer une contribution. Ils te donneront les codes, les règles et les procédures à respecter pour la consistance et maintenance du projet.

**Le code de conduite (code of conduct)**

**La plupart des projets open source écrivent un code de conduite.** Il permet de définir des règles et des comportements à adopter ou non sur le projet.

Les points essentiels de ce code définissent les règles à suivre entre les participants. Savoir respecter les différents points de vue, écouter et accepter les feedbacks sur ses contributions. Il faut s'attendre à de potentiels désaccords. Il ne faut pas les prendre personnellement. Parfois, lors des revues, il est possible que l'on ne soit pas du même avis sur certaines décisions ou approches adoptées. Il est alors très important de rester professionnel et respecter le code de conduite. Tout feedback est bon à prendre et c'est lors de ce type de discussion que l'on apprend le plus.

**Il est également très important d’être patient.** De nombreux projets open source sont maintenus sur le temps personnel. Il peut donc se passer un certain temps avant que sa contribution ne soit relue ou acceptée.

Voici un exemple de code de conduite utilisé par de nombreux projets : [*Contributor convenant*](https://www.contributor-covenant.org/). Les règles qu'il définit devraient être appliquées autant dans les projets open source que dans le milieu professionnel.

**Le guide de contribution**

Il permet de définir les workflows et les manières de coder sur le projet afin de comprendre les normes et les attentes de la communauté. Par exemple :
* Comment mettre en place mon environnement de développement ?
* Comment poster une issue ?
* Quelles sont les normes de commit ?
* Quelles sont les attentes sur les tests ?
* …

Si une contribution ne suit pas ces bonnes pratiques, il se peut qu'elle soit rejetée avant même d'avoir été revue. Ces normes servent à garder une cohérence dans le projet mais également à faire gagner du temps aux mainteneurs du projet. Donc à lire avec attention.

**Rejoindre la communauté**

Un projet ne se limite pas à la documentation et au code source. Il est également important de comprendre et d’interagir avec la communauté du projet. Il y a différents rôles dans un projet open source, les trois principaux étant :
* Les mainteneurs ou core contributors, qui sont à l’origine du projet ou ont intégré ce rôle suite à l’ensemble des contributions qu’ils ont réalisées.
* Les contributeurs, qui participent à la vie du projet en proposant des contributions (documentation, correction de bug...) mais également en répondant à des questions ou des tickets des utilisateurs.
* Et les utilisateurs, qui vont bien sûr utiliser le projet mais surtout donner des feedbacks, poster des bugs, proposer des améliorations ou poser des questions sur des forums.

Les moyens de communication de la communauté varient en fonction des projets. Il peut s'agir d'une mailing list, d'un Slack, d'un Discord ou tout autre outil du même type. Elle permet de poser des questions, d'aider à définir les roadmaps, ou tout simplement de discuter entre passionnés.



## Première contribution 🐥

Maintenant que tu as identifié un projet qui t'intéresse et que tu as lu la documentation nécessaire pour bien démarrer, tu es prêt à proposer ta première contribution.

Avant tout, sache que tu n'as pas besoin de savoir coder pour contribuer sur des projets open source :
* Tu aimes écrire ? Corrige ou développe la documentation du projet.
* Tu maîtrises le design ? Crée le logo ou le site du projet.
* Tu aimes communiquer ? Réponds aux questions de la communauté.

Toutes les contributions sont bonnes et servent au projet. Voici une liste non exhaustive des tâches que tu peux réaliser pour aider les projets open source :

**Documentation**

* Écrire et corriger la documentation du projet ;
* traduire la documentation.

**Organisation**

* Soumettre des bugs ou nouvelles fonctionnalités ;
* répondre aux issues, les classer et les fermer si nécessaire ;
* répondre aux questions (p. ex. sur GitHub, Stack Overflow…).

**Communication**

* Écrire des articles ou tutoriels ;
* organiser des meetups ou conférences sur le projet ;
* communiquer sur twitter (nouvelles releases, contributions…) ;
* réaliser un design pour le projet (logo, couleurs…) ;
* développer un site pour le projet.

**Coder**

* Réaliser des revues de codes ;
* développer les tests ;
* automatiser le projet (CI…) ;
* corriger des bugs ;
* réaliser de nouvelles fonctionnalités.

Si tu ne sais pas par où commencer, parcours la liste des issues ouvertes sur le projet. Dans beaucoup de projets, certains tickets sont identifiés comme *« Good First Issues »* ou *« Beginner »*. Ils ont été identifiés par les contributeurs principaux comme des contributions simples et de bons points d'entrée dans le projet. Regarde également les tickets catégorisés « Help needed » qui attendent qu'un contributeur prenne le sujet en main.

Quand tu as identifié une issue ou un ticket sur lequel tu souhaites contribuer, il faut te positionner dessus. Il ne faut pas hésiter à demander des informations aux autres contributeurs. Le dialogue et l'échange sont essentiels pour correctement démarrer une nouvelle contribution. Ils permettront de t'orienter vers les attentes de la communauté, de valider une solution technique ou d'identifier certaines contraintes ou difficultés.

Avant de publier ta première contribution, vérifie ton code et n'oublie pas les tests avant de le soumettre. Il ne faut pas hésiter à expliquer le contexte et documenter sa contribution. Tout ce qui pourra aider les autres contributeurs et mainteneurs à relire ta contribution fera qu'elle sera revue et intégrée plus rapidement.

Enfin, quand tu auras réalisé ta première contribution, n'oublie pas de communiquer dessus et de la partager au monde entier sur Twitter, Facebook, ou ton réseau social favori 😊.
