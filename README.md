# blank-exercises

Exercices pour la formation _blank

## How-To : Résoudre un exercice.
- Aller dans le clone local de votre repo
- Créer une branche avec le même nom que le dossier où est situé l'exercice
    - Exemple : si l'exercice est dans `html/lesson1/exercise1`, créer une branche `html/lesson1/exercise1` depuis la branche _master_.
    - `git checkout master` puis `git checkout html/lesson1/exercise1`
- Résoudre l'exercice dans le même dossier.
- Pousser (push) votre code vers le _repo_ distant.
    - Exemple : `git push origin html/lesson1/exercise1`.
- Ouvrir une nouvelle _pull request_ :
    - De votre branche
    - Vers la branche master
    - Sur votre repo ! (pas vers la source du fork !)
- Attendre la correction (validation de la _pull request_ par le professeur).
    - Corriger les remarques eventuelles et les pousser.
- _Merger_ la _pull request_ sur GitHub.
- Supprimer la branche source.
- Revenir sur la branche _master_.
- Récuperer (_pull_) les modifications sur la branche _master_.
    - `git pull --rebase`

## How-To : Mettre en place les exercices
- Demander au professeur de vous créer votre repo
- Le cloner :

```
git clone https://github.com/blank-4/blank-exercises_<TRIGRAMME>
```

## How-To : Mettre en place les exercices (à faire par le professeur).

Avant toute chose, il faut avoir forké le [projet](https://github.com/blank-project/blank-exercises) sur GitHub.

![Fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)

Le fork doit être réalisé dans l'organisation [\_blank 2018-2019](https://github.com/blank-4)

- Renommer le fork `blank-exercises_<TRIGRAMME>`
    - TRIGRAMME : Première lettre du Prénom + Deux Premières lettre du nom
- Paramétrer le repo :
 - Désactiver le Wiki
 - Désactiver les Projets ?
 - TODO Quel mode de merge ? Squash ou Merge Commit ? Pas rebase à mon avis.
- Paramétrer les permissions :
  - L'apprenant a les droits *Write* sur le repo
  - L'équipe *Teachers* a les droits *Admin* sur le repo
  - La Team *Learners* n'a pas accès au repo personnel
 - Paramétrer les restrictions de branche :
   - Approval nécessaires pour merger une Pull Request : 1
   - la Team *Teachers* étant la seule (en dehors du user) à avoir les accès en lecture, elle est la seule à pouvoir review.
