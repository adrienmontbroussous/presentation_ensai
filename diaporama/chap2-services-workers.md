### Contexte

### Les Progressive Web Apps

## Les Service Workers

### IndexedDb

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Qu'est-ce qu'un service worker ?

## Principe

C'est un script (javaScript) tournant en fond de notre application et interceptant les requêtes.

<img src="images/service-worker.jpg" width="700px" />

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Besoin d'un environnement sécurisé

- Pas de certificat valide => pas de mise en cache
- Cela a été problématique au cours de mes tests et du projet

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Stratégies principales de mise en cache

|                                                                                       |                                                                                                   |
| ------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |
| À l'installation <img src="images/cm-on-install-dep.png" width="300px" />             | Quand une requête au réseau réussit <img src="images/cm-on-network-response.png" width="300px" /> |
| Lors d'une mise à jour planifiée <img src="images/cm-on-bg-sync.png" width="300px" /> |

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Stratégies principales d'utilisation du cache

|                                                                                                  |                                                                                        |
| ------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------- |
| Seulement le cache <img src="images/ss-cache-only.png" width="400px" />                          | Seulement le réseau<img src="images/ss-network-only.png" width="400px" />              |
| Le réseau sinon le cache <img src="images/ss-network-falling-back-to-cache.png" width="400px" /> | Course entre les deux <img src="images/ss-cache-and-network-race.png" width="400px" /> |

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Mise en place

- Create React App
- Workbox

%%%

<!-- .slide: class="slide" data-background-image="images/logo-git.png" data-background-size="600px" -->

### Des outils d'aide au développement

- La console embarquée au navigateur Chrome
- L'environnement de développement Visual Studio Code
