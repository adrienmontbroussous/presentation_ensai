<!-- .slide: data-background-image="images/pwa.png" data-background-size="600px" class="chapter" -->

## 3

### IndexedDb : une (des) solution(s) pour stocker les données localement

%%%

<!-- .slide: class="slide" data-background-color="#7580ba" -->

### Les ancêtres et les cousins d'IndexedDb

## Le Web Storage ou DOM Storage

- Stockage sous forme de couple clé / valeur
- Deux formes de stockage : LocalStorage ou Session Storage

## Les bases WebSql

- Api permettant de faire des requêtes asynchrones et transactionelles
- W3C a annoncé en novembre 2010 l'arrêt de la spécification

%%%

<!-- .slide: class="slide" data-background-color="#7580ba" -->

### Zoom sur indexedDb

C'est un peu un mix des deux précedents et c'est ce qui est à la mode.

- Tous les objets sont stockées sous format json.

Le requêtage

- ce sont des appels asynchrones
- sympa de pouvoir utiliser des indexs (on va vous montrer un exemple plus tard)

%%%

<!-- .slide: class="slide" data-background-color="#7580ba" -->

### Comment mettre ça en place, FrameWork ou pas Framework?

Les limites liées à l'utilisation d'un framework

- maintien de la communauté
- mise à jour

%%%

Ou aller voir ?
NPM -> store avec la liste de tous les framework js
Gestionnaire de dépendance // avec maven pour java

%%%

- Comment gérer les changements de modèle de la BDD locale ?
  https://medium.com/@addyosmani/a-tinder-progressive-web-app-performance-case-study-78919d98ece0

<!-- .slide: class="slide" data-background-color="#7580ba" -->

Il y a pas mal de librairies différentes, nous on a choisi Dexie.js sur Prisme.

Ses Avantages:

- simplicité du code
- requêtes peu coûteuses
- gestion des erreurs

### DEMO !
