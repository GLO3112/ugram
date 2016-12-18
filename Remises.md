# Remises

Les remises ne seront pas effectuées par le portail des cours. Au contraire, les étudiants seront responsable de déployer leurs applications pour les enseignants.

Pour chaque livrable, les équipes devront suivre la procédure suivante:

* Créer une branche nommée release-X (où X est le numéro du livrable) dans le dépôt GitHub.
* Fournir un README du livrable avec les instructions pour les correcteurs.
* Le code du client devra être _compressé_ et _minifié_.
* Respecter les spécificités listées plus bas.

La branche **ne doit plus être touchée** une fois la date de remise passée. Une modification de la branche après la date de remise peut entraîner de fortes pénalités. Les correcteurs utiliserons le code directement sur GitHub.

## Livrable 1

Tel que dit dans l'énoncé, le livrable 1 devra utiliser l'API fournie par les enseignants.

Puisque le livrable ne consiste qu'en un livrable client, l'entièreté du code doit être déployé dans Amazon S3 sous forme de site statique. Voir la [documentation suivante](http://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html) pour la procédure et [cette documentation](http://docs.aws.amazon.com/AmazonS3/latest/dev/HostingWebsiteOnS3Setup.html) pour un exemple détaillé.

Le lien du site statique devra être inclus dans le README de la branche de release. Le site *ne devra aucunement être modifié* après la date de remise.

## Livrable 2

Le livrable 2 consiste en une remise de client et serveur. 

Il existe plusieurs possibilités de remise, mais la méthode proposée en est une hybride.

* Le serveur devrait être déployé dans Amazon Elastic Beanstalk et contenir le fichier _index.html_. Voir instructions et exemples [ici] (https://aws.amazon.com/documentation/elastic-beanstalk/). Vous devrez aussi configurer potentiellement une base de données avec RDS et exposer vos logs dans CloudWatch.
* Le code client (JS, CSS) devrait tout de même être déployé dans Amazon S3, et le fichier index.html devrait simplement pointer dessus.

Le lien de l'application Beanstalk devra être inclus dans le README de la branche de release. Le site *ne devra aucunement être modifié* après la date de remise. Il est donc recommendé de vous faire 2 environnments Beanstalk (development/production) afin de ne pas interférer.

## Livrable 3

Le livrable 3 consiste en une remise de client et serveur. 

La remise est sensiblement identique au livrable 2. Par contre, dans le README, vous devrez également inclure un (des) lien(s) vers vos _dashboards_ Google Analytics que les enseignants pourront consulter. Vous devrez également indiquer quelles fonctionnalités additionnelles vous avez choisi et le fonctionnement de leur implémentation respective.

Le lien de l'application Beanstalk devra être inclus dans le README de la branche de release. Le site *ne devra aucunement être modifié* après la date de remise. Il est donc recommendé de vous faire 2 environnments Beanstalk (development/production) afin de ne pas interférer.

Pour le livrable 3, les enseignants fourniront des noms de domaine et feront une association avec le lien de votre Beanstalk afin de vous permettre d'exposer une "vraie" application. Pratique pour un stage :)
