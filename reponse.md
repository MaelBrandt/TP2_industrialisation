# Reponse au questions

## 1b

Quelles étapes (steps) sont réalisées par cette action ?

- Set up Python 3.10
- Instale les dependences
- Lint avec flake8
- Test avec pytest

Une étape est définie au minimum par 2 éléments, lesquels sont-ils et
à quoi servent-ils ?

- name : nom de l'étape, utilisé pour réfèrer à l'étape
- run/uses : commandes exécutées par l'actions.

La première étape contient le mot-clé ‘with’, a quoi sert-il ?

- définir des paramêtres passé en input. ces paramêtres sont enregistré en tant que variable d'environnement.

## 2a

Sur l’onglet Summary d’une analyse de code, SonarCloud fournit 4 indicateurs.
Quels sont-ils et quelles sont leurs utilités ?

- Security : noumbre de vulnérabilité conteneu dans le code.
- Reliability : ???
- Maintainability : indicateur montrant si le code est facile à maintenir ou non.
- Duplications : pourcentage du code couvert par les tests de sonarcloud.

À quoi sert l’indicateur Quality Gate ?

- mesure booléenne permettant de voir rapidement si le code est près pour la production.
