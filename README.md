# blank-exercises

Exercices pour la formation _blank

## How-To : Mettre en place les exercices.

Avant toute chose, il faut avoir forké le [projet](https://github.com/blank-project/blank-exercises) sur GitHub.

![Fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Vous devez maintenant avoir un copie du _repo_ dans votre compte GitHub

Il faut ensuite cloner votre _fork_ du projet :

```
git clone https://github.com/YOUR-USERNAME/blank-exercises
```

## How-To : Résoudre un exercice.

- Créer une branche avec le même nom que le dossier où est situé l'exercice
    - Exemple : si l'exercice est dans `html/lesson1/exercise1`, créer une branche `html/lesson1/exercise1` depuis la branche _master_.
- Résoudre l'exercice dans le même dossier.
- Pousser (push) votre code vers le _repo_ distant.
    - Exemple : `git push origin html/lesson1/exercise1`.
- Ouvrir une nouvelle _pull request_.
- Attendre la correction (validation de la _pull request_ par le professeur).
    - Corriger les remarques eventuelles et les pousser.
- _Merger_ la _pull request_ sur GitHub.
- Revenir sur la branche _master_.
- Récuperer (_pull_) les modifications sur la branche _master_.
    - `git pull --rebase`
