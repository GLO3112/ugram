# Remises

Les remises ne seront pas effectuées par le portail des cours. Au contraire, les étudiants seront responsable de déployer leurs applications, et tout sera géré à partir du dépôt GitHub.

Pour chaque livrable, les équipes devront suivre la procédure suivante:

* Créer une branche nommée release-X (où X est le numéro du livrable) dans le dépôt GitHub.
* Fournir un README du livrable avec les instructions pour les correcteurs.
* Respecter les spécificités listées plus bas.

La branche **ne doit plus être touchée** une fois la date de remise passée. Une modification de la branche après la date de remise peut entraîner de fortes pénalités. Les correcteurs utiliseront le code directement sur GitHub.

## Livrable 0

Le livrable 0, également appelé _design_ sur le portail des cours, consiste en un simple document décrivant l'architecture de votre projet et les technologies que vous désirez utiliser. Ce document devrait être écrit à même le README du dépôt GitHub, et comprendre les éléments suivants:

* Frameworks choisis pour le frontend
* Langage choisi pour le backend
* Frameworks choisis pour le backend: framework REST, ORM, logging, etc.
* Base de données choisie
* CI/CD choisi
* Méthode de déploiement si différente de celle proposée plus bas (si vous n'êtes pas certains, simplement mentionner que le déploiement suivra les méthodes démontrées dans le cours)
* Tout autre information pertinente à l'architecture si désirée

Le but du livrable 0 est simplement que l'enseignant s'assure que les équipes soient sur le bon chemin pour la réalisation du projet.

## Livrable 1

Le livrable 1 consiste en une remise de client et serveur, sans déploiement pour l'instant.

Puisque l'application n'est pas encore déployée, les étudiants devront fournir un **docker compose** contenant l'application et toutes ses dépendances (base de donnée, notamment). Les correcteurs ne devraient qu'avoir à rouler docker pour faire fonctionner l'application. Toute manipulation supplémentaire entrainera de fortes pénalités.

Les instructions pour rouler l'application devront être incluses dans le README de la branche de release. L'application *ne devra aucunement être modifiée* après la date de remise.

## Livrable 2

Le livrable 2 consiste en une remise de client et serveur et inclut le déploiement. 

Il existe plusieurs possibilités de remise, mais la méthode proposée en est une hybride.

* L'entièreté du code frontend devrait être déployé dans Amazon S3 sous forme de site statique. Voir la [documentation suivante](http://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html) pour la procédure et [cette documentation](http://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html) pour un exemple détaillé.
* Le serveur devrait être déployé dans Amazon Elastic Beanstalk. Voir instructions et exemples [ici](https://aws.amazon.com/documentation/elastic-beanstalk/).

Le lien de l'application (lien S3 ou Cloudfront) devra être inclus dans le README de la branche de release. Le site *ne devra aucunement être modifié* après la date de remise. Il est donc recommandé de vous faire 2 environnements AWS afin de ne pas interférer.

## Review intermédiaire

Vous trouverez sur le portail des cours un livrable nommé *review intermédiaire*, situé entre les livrables 2 et 3.
Il s'agit simplement d'une plage horaire qui sera attribuée à votre équipe afin de discuter de votre travail avec le correcteur.
Au minimum un membre de l'équipe doit être présent durant la plage attribuée.

De plus amples informations seront données par l'enseignant au courant de la session.


## Livrable 3

Le livrable 3 consiste en une remise de client et serveur.

La remise est sensiblement identique au livrable 2. Par contre, dans le README, vous devrez également expliquer la stratégie/les outils de _monitoring_ que vous employez pour votre application. Vous devrez également indiquer quelles fonctionnalités additionnelles vous avez choisi et le fonctionnement de leurs implémentations respectives.

Le lien de l'application (lien S3 ou Cloudfront) devra être inclus dans le README de la branche de release. Le site *ne devra aucunement être modifié* après la date de remise. Il est donc recommendé de vous faire 2 environnements AWS afin de ne pas interférer.
