<!-- .slide: data-background-image="images/pwa.png" data-background-size="600px" class="chapter" -->

## 4

### IndexedDb : une (des) solution(s) pour stocker les données localement

stocker des données plus volumineuses et structurées, et interagir avec elles?

%%%

<!-- .slide: class="slide" data-background-color="#7580ba" -->

### Zoom sur indexedDb

- Tous les objets sont stockées sous format json.

Le requêtage

- ce sont des appels asynchrones
- possibilité d'utiliser des index

%%%

### Mise en place, FrameWork ou pas Framework?

Les limites liées à l'utilisation d'un framework

- maintien de la communauté
- mise à jour

%%%

Où aller voir ?

https://www.npmjs.com/

%%%

Il y a pas mal de librairies différentes, nous on a choisi Dexie.js sur Prisme.

Ses Avantages:

- communauté active
- syntaxe pour les requêtes indexées intuitive
- compatible avec react

%%%

Et en production quelles problématiques ?

- montée de version de la base de données par fichier json

<img src="images/schemaOriginal_rogne.png" width="500px" />

<img src="images/maj1_rogne.png" width="500px" />
