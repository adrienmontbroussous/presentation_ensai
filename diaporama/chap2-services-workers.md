<!-- .slide: data-background-image="images/pwa.png" data-background-size="600px" class="chapter" -->

## 2

### Les Service Workers

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Qu'est ce qu'un service worker ?

## Principe

C'est tout simplement un script (javaScript) tournant en fond de notre application et interceptant les requêtes.

<img src="images/service-worker.jpg" width="700px" />

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Qu'est ce qu'un service worker ?

## Quelles contraintes pour mettre en place les services worker?

<img src="images/important-notes.png" width="800px" />

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Stratégies principales de mise en cache

|                                                                             |                                                                                                    |
| --------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------- |
| A l'installation <img src="images/cm-on-install-dep.png" width="300px" />   | Quand une requête au network réussit <img src="images/cm-on-network-response.png" width="300px" /> |
| Mise à jour plannifiée <img src="images/cm-on-bg-sync.png" width="300px" /> | Quand on reçoit une notification <img src="images/cm-on-push.png" width="300px" />                 |

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Stratégies principales d'utilisation du cache

|                                                                                             |                                                                            |
| ------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| Seulement le cache <img src="images/ss-cache-only.png" width="400px" />                     | Seulement le network<img src="images/ss-network-only.png" width="400px" /> |
| Network sinon cache <img src="images/ss-network-falling-back-to-cache.png" width="400px" /> | course <img src="images/ss-cache-and-network-race.png" width="400px" />    |
