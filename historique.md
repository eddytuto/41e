# Historique des commandes du TP1

### Création d'un dépôt

- Initialise un dépôt vide, cette commande est exécuté une seule fois
- Si on l'exécute une deuxième fois on détruit le dépôt
- `git init`

---

### Vérifier le statut 
- `git status`
---
### Afficher l'historique des commits
- `git log`
- `git log --oneline`
---
### Naviguer dans les branches
- Pour changer le nom d'une branche
    - `git branch -m «nom nouvelle branche»`
    - `git branch -m main`  // change le nom de la branche courante pour main
- Pour créer une nouvelle branche
    - `git branch « nouvelle branche »`
- Pour changer de branch 
    - `git checkout « la branche »`
    - On ne peut pas changer de branche si la branche courante n'a pas été «commit» valider 
    - `git checkout « id du commit »`
    - `git checkout « étiquette du commit »`   
- Pour créer une étiquette
    - `git tag v1.0.0` // Création de l'étiquette v1.0.0
    - `git tag` // permet d'afficher l'ensemble des tag (étiquette)   
    - `git checkout v1.0.0` // pour se déplacer dans le commit v1.0.0 (déplace le pointeur «head»)
