# Guide de Contribution

Nous sommes ravis que vous souhaitiez contribuer à notre projet ! Ce document vous guidera sur la manière de contribuer efficacement.

## Comment Contribuer

### Rapporter des Bugs

Si vous trouvez un bug, veuillez vous assurer qu'il n'a pas déjà été signalé en consultant les [Issues](https://github.com/melvinvallot/decode_projet_git/issues) sur GitHub.

Si vous ne trouvez pas de rapport existant, ouvrez une nouvelle "issue". Assurez-vous d'inclure :

- Un titre clair et descriptif.
- Une description aussi détaillée que possible du problème.
- Les étapes pour reproduire le bug.
- La version du projet que vous utilisez.
- Votre environnement (navigateur, système d'exploitation, etc.).

### Suggérer des Améliorations

Si vous avez une idée pour une nouvelle fonctionnalité ou une amélioration, ouvrez une "issue" pour en discuter. Cela nous permet de nous assurer que votre suggestion correspond à la direction du projet avant que vous ne commenciez à travailler dessus.

## Processus de Développement

1.  **Forkez** le dépôt sur GitHub.
2.  **Clonez** votre fork en local :
    ```bash
    git clone https://github.com/melvinvallot/decode_projet_git.git
    ```
3.  Créez une nouvelle **branche** pour vos modifications :

    ```bash
    git checkout -b nom-de-votre-branche
    ```

    (par exemple, `feature/nouvelle-fonctionnalite` ou `fix/correction-bug`).

4.  Effectuez vos modifications. Assurez-vous de suivre les conventions de codage du projet.

5.  **Commitez** vos changements avec un message clair et concis :

    ```bash
    git commit -m "Ajout de la fonctionnalité X"
    ```

6.  **Poussez** vos changements vers votre fork :

    ```bash
    git push origin nom-de-votre-branche
    ```

7.  Ouvrez une **Pull Request** (PR) depuis votre fork vers la branche `main` (ou `develop`) de notre dépôt.

8.  Dans votre PR, décrivez les changements que vous avez effectués et liez-la à l'issue correspondante si applicable.

## Conventions de Style de Code

- **JavaScript :** [Précisez vos conventions, ex: StandardJS, Airbnb, etc.]
- **CSS :** [Précisez vos conventions, ex: BEM, SMACSS, etc.]
- **Git :** Les messages de commit doivent être clairs et suivre un format standard (ex: `feat:`, `fix:`, `docs:`, etc.).

Merci de votre contribution !
