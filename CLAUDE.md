# Portfolio Thomas-RichardLeclerc



Site personnel publié sur GitHub Pages à l'adresse thomas-richardleclerc.github.io.



## Contraintes techniques



- HTML et CSS purs. Aucun framework, aucune dépendance npm.

- Pas d'outil de build : les fichiers du dépôt sont servis tels quels.



## Workflow Git



- Jamais de commit direct sur `main`.

- Une issue, puis une branche, puis une pull request qui ferme l'issue avec `Closes #n`.

- Après le merge : supprimer la branche sur le serveur, en local, puis `git fetch --prune`.



## Publication



- GitHub Actions publie le site automatiquement à chaque merge sur `main`.

- Ne pas modifier les fichiers générés par le workflow.



## Langue



- Répondre en français.

