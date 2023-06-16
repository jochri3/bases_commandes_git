TP

2.1. Exercice de base :

- Initialisez un nouveau dépôt Git dans un répertoire vide.
- Créez une structure de répertoires comprenant un dossier principal et des sous-dossiers.
- Ajoutez des fichiers HTML, CSS et JavaScript à différents niveaux de la structure de répertoires.
- Effectuez des modifications dans différents fichiers et effectuez des commits avec des messages descriptifs.
- Utilisez `git log --graph` pour visualiser l'historique des commits avec la structure de branches.

  2.2. Exercice de branches avancé :

  - Créez une branche "feature-user-authentication" à partir de la branche principale.
  - Implémentez un système d'authentification utilisateur dans votre application en ajoutant des fichiers et en effectuant des modifications.
  - Effectuez des commits fréquents avec des messages clairs décrivant chaque étape de l'implémentation.
  - Revenez à la branche principale et créez une autre branche "feature-payment-gateway".
  - Ajoutez un système de paiement à votre application en modifiant et en ajoutant des fichiers.
  - Effectuez des commits réguliers en utilisant des messages significatifs.
  - Fusionnez les branches "feature-user-authentication" et "feature-payment-gateway" dans la branche principale, en résolvant les conflits si nécessaire.

    2.3. Exercice de collaboration complexe :

  - Travaillez en équipe de trois étudiants.
  - Créez un dépôt Git sur une plateforme en ligne et partagez les informations d'accès avec les membres de l'équipe.
  - Chaque membre de l'équipe crée une branche et travaille sur une fonctionnalité spécifique de l'application.
  - Effectuez des commits réguliers avec des messages descriptifs dans chaque branche.
  - Utilisez `git fetch` et `git merge` pour synchroniser les branches des membres de l'équipe et résoudre les conflits si nécessaire.
  - Fusionnez les branches des fonctionnalités dans une branche "develop" et testez l'application.
  - Lorsque l'application est stable, fusionnez la branche "develop" dans la branche principale (par exemple, `master` ou `main`) pour la livraison finale.

    2.4. Exercice avancé de gestion des tags :

  - Créez un tag annoté "v1.0" pour marquer la première version stable de votre projet.
  - Effectuez plusieurs commits supplémentaires et ajoutez des fonctionnalités à l'application.
  - Créez un autre tag annoté "v2.0" pour marquer une version majeure du projet.
  - Utilisez `git tag -a` pour inclure des informations détaillées sur chaque version dans les tags annotés.
  - Utilisez `git diff` pour comparer les différences entre les versions marquées par les tags.

Correction

Bien sûr ! Voici une correction pour le TP basé sur les exercices mentionnés précédemment :

1. Exercice de base :

   - Correction :
     - Créez un dépôt Git local en utilisant `git init`.
     - Créez un fichier `index.html` avec du code HTML.
     - Utilisez `git add index.html` pour ajouter le fichier à la staging area.
     - Effectuez un commit en utilisant `git commit -m "Initial commit"`.
     - Modifiez le contenu du fichier `index.html`.
     - Utilisez `git add index.html` pour mettre à jour les modifications.
     - Effectuez un nouveau commit en utilisant `git commit -m "Updated index.html"`.

2. Exercice de branches :

   - Correction :
     - Utilisez `git branch feature-login` pour créer une nouvelle branche appelée "feature-login".
     - Modifiez le fichier `index.html` pour ajouter un formulaire de connexion.
     - Ajoutez les modifications à la staging area avec `git add index.html`.
     - Effectuez un commit avec le message "Added login form" en utilisant `git commit -m "Added login form"`.
     - Revenez à la branche principale en utilisant `git checkout master` (ou `main`).
     - Créez une nouvelle branche "feature-about" avec `git checkout -b feature-about`.
     - Modifiez le fichier `index.html` pour ajouter une section "À propos".
     - Ajoutez les modifications à la staging area avec `git add index.html`.
     - Effectuez un commit avec le message "Added about section" en utilisant `git commit -m "Added about section"`.
     - Fusionnez les branches avec `git merge feature-login` et `git merge feature-about`.

3. Exercice de collaboration :

   - Correction :
     - Un étudiant crée un dépôt Git sur une plateforme en ligne (par exemple, GitHub) et partage le lien avec les autres étudiants.
     - Les autres étudiants clonent le dépôt sur leur machine locale en utilisant `git clone <url_du_dépôt>`.
     - Chaque étudiant crée une nouvelle branche avec `git branch` ou `git checkout -b`.
     - Chaque étudiant effectue des modifications dans leurs branches respectives.
     - Chaque étudiant ajoute et committe ses modifications avec des messages descriptifs.
     - Les étudiants utilisent `git push` pour envoyer leurs commits vers le dépôt distant.
     - Les étudiants fusionnent leurs branches en utilisant `git merge` ou en créant des demandes de fusion (pull requests) selon la plateforme en ligne utilisée.

4. Exercice de gestion des tags :
   - Correction :
     - Créez un tag léger avec `git tag v1.0` ou un tag annoté avec `git tag -a v1.0 -m "Version 1.0"`.
     - Effectuez plusieurs commits supplémentaires.
     - Créez un autre tag avec `git tag v2.0` ou `git tag -a v2.0 -m "Version 2.0"`.
     - Utilisez `git checkout <tag_name>` pour revenir à chaque version marquée par un tag et vérifiez le code correspondant.

Avec ces exercices, pour avez toutes les bases de Git pour aborder le module Java le vendredi 16 juin 2023.
