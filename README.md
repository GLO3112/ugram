# ugram

ugram est le dépôt contenant toutes les ressources nécessaires à la réalisation du projet de session du cours Développment d'applications web avancé. Le projet est réalisé en équipe de 4 à 6 et comporte 3 livrables. Les étudiants auront à réaliser le frontend et le backend de l'application.

Il est bien important de lire les pages suivantes:

* [Énoncé](https://github.com/GLO3112/ugram/blob/master/Enonce.md)
* [Remises](https://github.com/GLO3112/ugram/blob/master/Remises.md)
* [Grille de correction](https://docs.google.com/spreadsheets/d/1C52Qwlf5l4wu_2_SGlAbJ6PKlXMl4jJfihJuSchRRSM/edit?usp=sharing)

## API livrable 1

L'API est fournie pour le livrable 1 et disponible à [l'adresse suivante](http://api.ugram.net/).

La documentation de l'API est disponible à [l'adresse suivante](http://api.ugram.net/docs).

L'API supporte également un exemple de _Login with Facebook_, à voir [ici](http://api.ugram.net/login). À noter que certaines requêtes sur l'API nécessitent d'être authentifiées. Lors de votre première utilisation, vous devrez vous enregistrer. Vous serez redirigé à /?token=SOMETHING. **NOTEZ BIEN LA VALEUR DE CE TOKEN!** Il devra être utilisé pour les requêtes authentifiées, dans le _header_ Authorization sous la forme _Bearer SOMETHING_.

Finalement, il est possible de voir un exemple de formulaire d'upload d'images à [l'adresse suivante](http://api.ugram.net/test/upload).

## Compte AWS

Chaque équipe devra posséder un compte AWS Free. Voir les détails [ici](https://aws.amazon.com/free/). Il est important de prendre conscience des limitations que le compte Free offre. Les enseignants se dégagent de tout coût supplémentaire entrainé par le dépassement de ces limites.

## Noms de domaine

Si voulu, les étudiants pourront fournir/demander un nom de domaine aux enseignants s'ils désirent exposer leur application à l'externe.

## Développement

Les étudiants devront développer le frontend de l'application en _TypeScript_. Le backend peut être développé en _Java_ ou en _NodeJs_, au choix. Les étudiants sont invités à se procurer [WebStorm](https://www.jetbrains.com/webstorm/) ainsi que [Eclipse](http://www.eclipse.org/downloads) ou [IntelliJ](https://www.jetbrains.com/idea) pour le développement _Java_. Les étudiants auront des dépôts Git fournis par les enseignants pour leurs projets. 

Pour le frontend, les technos suivantes *doivent* être utilisées:
* [TypeScript](https://www.typescriptlang.org/)
* [SASS](http://sass-lang.com/) ou [LESS](http://lesscss.org/) ou [PostCSS](http://postcss.org/)
* [Gulp](http://gulpjs.com/) et/ou [Webpack](https://webpack.github.io/)

Pour le backend, les technologies sont un peu plus libres mais doivent s'intégrer avec AWS si applicable.

## _Starter Packs_

Afin de bien commencer le projet, les enseignants fournissent des _starter packs_ avec les dépendances minimales nécessaires. À vous de choisir la techno qui vous plait!

* [frontend-starter-packs](https://github.com/GLO3112/frontend-starter-packs)
* [backend-starter-packs](https://github.com/GLO3112/backend-starter-packs)
