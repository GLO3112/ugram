# Énoncé du projet de session

Le projet de session consiste à développer une application web similaire à [Instagram](https://www.instagram.com).  Les étudiants devront développer les parties client ET serveur de l'application. Il est très important pour les étudiants de lire les sections [Remises](https://github.com/GLO3112/ugram/blob/master/Remises.md) et [Grille de correction](https://docs.google.com/spreadsheets/d/1C52Qwlf5l4wu_2_SGlAbJ6PKlXMl4jJfihJuSchRRSM). Les remises seront passablement différentes des autres cours!

Le projet doit être fait en équipe de 4 à 6 étudiants. L’équipe doit utiliser les dépôts GitHub et les _starter packs_ fournis par les enseignants. L'application doit être réalisée en *anglais*. 

Voir dates de remise sur le portail des cours.

## Livrable 1

Le livrable 1 ne consiste qu'en développement de la partie client de l'application. Il devra utiliser l'API fournie par les enseignants. La documentation de l'API sera fournie, mais pas le code. Afin de créer un usager, les étudiants pourront utiliser l'API fournie. La partie client devra être développée en TypeScript. 

Les fonctionnalités suivantes devront être implémentées:
* L'usager doit pouvoir consulter son profil usager.
 * Photo de profil
 * Nom d'usager
 * Email
 * Date d'inscription
* L’usager doit pouvoir éditer son profil usager.
 * Photo de profil
 * Nom d'usager
 * Email
* L'usager doit pouvoir consulter la liste des usagers.
* L'usager doit pouvoir consulter le profil d'un usager ainsi que ses images.
* L'usager doit pouvoir téléverser une image avec les champs suivants.
 * Description
 * Mots clés (hashtags)
 * Mention d'un usager
* L'usager doit pouvoir modifier les champs d'une de ses images.
* L'usager doit pouvoir supprimer une de ses images.
* L'usager doit pouvoir consulter ses images.
* L'usager doit pouvoir consulter une de ses images en particulier.
* L'usager doit pouvoir consulter une liste d'images ordonnées par date, tout usager confondu.

## Livrable 2

Le livrable 2 consiste au développement de la partie client ET de la partie serveur de l'application, ainsi que quelques fonctionnalités supplémentaires. L'API développée devra _en tout point_ respecter celles offertes par les enseignants au livrable 1 (les enseignants devraient pouvoir prendre le livrable 1 et le mettre sur votre API sans aucune modification). La partie serveur peut être développée en Java ou NodeJS, au choix.

**Note**: À partir du livrable 2, les opérations d'édition ne devraient pas être permises pour un usager n'ayant pas les droits requis (Ne pas supprimer une image d'un autre usager, par exemple...)

En addition des fonctionnalités du livrable 1, les fonctionnalités suivantes devront être implémentées:

* L'usager doit pouvoir s'authentifier dans l'application en utilisant un fournisseur OAuth connu. (Facebook, Google etc.)
* S'il ne possède pas de compte, l'usager doit pouvoir s'enregistrer dans l'application.
* L'usager doit pouvoir se déconnecter de l'application.
* L'usager doit pouvoir supprimer son compte.
* L'usager doit pouvoir rechercher un autre usager.
* L'usager doit pouvoir rechercher pour des images contenant un mot précis dans leur description.
* L'usager doit pouvoir rechercher pour des images contenant un mot clé (hashtag) précis.

## Livrable 3

Le livrable 3 consiste au développement de la partie client ET de la partie serveur de l'application.

Les fonctionnalités suivantes devront être implémentées:

* L'usager doit pouvoir réagir aux images d'un autre usager.
* L'usager doit pouvoir commenter les images d'un autre usager.
* L'usager doit pouvoir consulter les réactions et commentaires sur l'une de ses images.
* L'usager doit pouvoir recevoir des notifications lorsqu'un usager réagit ou commente sur l'une de ses images.
* L’application doit gérer le _resizing_ des images téléchargées et offrir les images en différents formats.
* L'application doit produire des analytiques sur le comportement de ses usagers.

Les fonctionnalités suivantes sont aux choix des étudiants. Chaque fonctionnalité possède un nombre de points associé, et l'équipe doit implémenter au minimum **15** points. La fonctionnalité doit être complète et fonctionnelle afin de recevoir le nombre de points associé, assurez-vous de choisir judicieusement...

* (3) L'usager doit pouvoir envoyer un message privé à un autre usager
* (5) L'usager doit pouvoir rechercher par mot clé ou description avec autocomplétion
* (8) L'usager doit pouvoir discuter en temps réel avec un autre usager
* (8) L'usager doit pouvoir se faire recommander les comptes d'usager les plus populaires
* (10) L'usager doit pouvoir se faire recommander des compes d'usager basés sur ses intérêts
* (10) L'usager doit pouvoir être intégrée avec un autre fournisseur de photos (Google Photos..)
* (5) L'usager doit pouvoir consulter les mots-clés les plus populaires
* (5) L'usager doit pouvoir appliquer des filtres sur ses photos lors du téléversement
* (5) L'usager doit pouvoir dessiner sur la photo lors du téléversement
* (5) L'usager doit pouvoir prendre une photo avec sa webcam

Encore une fois, consultez la section [Remises](https://github.com/GLO3112/ugram/blob/master/Remises.md) ! Bonne chance.

