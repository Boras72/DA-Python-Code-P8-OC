Créer un Repo sur GitHub :

### Sur GitHub :

1. **Créer un nouveau dépôt** :
   - Allez sur [GitHub](https://github.com/) et connectez-vous à votre compte.
   - Cliquez sur le bouton "New repository" ou allez à [Create a new repository](https://github.com/new).
   - Remplissez les détails de votre dépôt :
     - **Repository name** : Donnez un nom à votre dépôt.
     - **Description** : (Facultatif) Ajoutez une description de votre projet.
     - **Public/Private** : Choisissez si vous voulez que votre dépôt soit public ou privé.
     - Ne cochez pas "Initialize this repository with a README" si vous avez déjà un projet local.
   - Cliquez sur "Create repository".

### Dans votre terminal :

2. **Initialiser le dépôt local et pousser sur GitHub** :
   - Ouvrez votre terminal et allez dans le répertoire de votre projet.
   - Initialisez un dépôt Git local :
     ```sh
     git init
     ```
   - Ajoutez vos fichiers au dépôt :
     ```sh
     git add .
     ```
   - Faites un commit de vos fichiers :
     ```sh
     git commit -m "Initial commit"
     ```
   - Ajoutez le dépôt distant que vous avez créé sur GitHub :
     ```sh
     git remote add origin https://github.com/<votre_nom_d_utilisateur>/<nom_du_depot>.git
     ```
     Remplacez `<votre_nom_d_utilisateur>` et `<nom_du_depot>` par votre nom d'utilisateur GitHub et le nom du dépôt que vous avez créé.
   - Poussez vos fichiers vers GitHub :
     ```sh
     git push -u origin main
     ```
     Si votre branche principale s'appelle "master" au lieu de "main", utilisez "master" à la place de "main" dans la commande ci-dessus.

### Vérification :

3. **Vérifiez sur GitHub** :
   - Allez sur la page de votre dépôt sur GitHub et vérifiez que vos fichiers ont bien été poussés.
