## Le sujet

Doc sur moodle

%%%

## SUJET

- L’objectif de ce projet va être de se servir de ces api afin de récupérer des données, créer des questions et réaliser une application de type “quizz”.
- Le choix de la série ou du film pourra être laissé libre sous réserve de trouver ou réaliser une api permettant de récupérer au format JSON ou XML les citations.
- L’exemple proposé par le tuteur est la série Kaamelott (api : https://kaamelott.chaudie.re/)

%%%

### Fonctionnalités

- choix de l’utilisateur répondant aux questions à l’entrée sur l’application
- série de questions
  - l’utilisateur choisit a son entrée le nombre de questions auxquelles il devra répondre
  - dans un premier temps les questions seront des question à choix multiple avec 4 propositions dont une correcte, à vous de voir comment seront choisies les mauvaises propositions.
  - dans un second temps on proposera le choix avant de répondre duo, kaarré ou kaash : chaque choix rapportant un nombre de point différent
- sauvegarde des scores réalisés par les utilisateurs à la fin de chaque série de question
- Tableaux avec l’historique des scores réalisés (utilisateur, mode, nombre de question, nombre de question juste, taux de réussite, temps de réponse (optionnel))

%%%

### Précision

- Il faudra trouver une manière de créer les questions : appeler l’api choisie pour remplir notre base avec des informations initialement et/ou l’appeler à chaque question.

%%%

### Fonctionnalités avancées

- consultation de haut faits : réponse la plus rapide, plus grande série sans erreur…
- timer (limiter le temps de réponse autorisé à chaque question)
- proposer des difficultés (à vous de choisir des critères)
- mélange de plusieurs séries/films
- Mode multijoueur
