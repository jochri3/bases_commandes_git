1. `git init` : Permet de créer un dépôt Git local dans le répertoire actuel.
2. `git clone <url>` : Clone le dépôt Git spécifié par l'URL, permettant ainsi d'obtenir une copie locale complète du dépôt.
3. `git status` : Affiche l'état des fichiers en indiquant les changements qui sont en attente d'être ajoutés (staging area) et ceux qui ne le sont pas encore.
4. `git add <nom_du_fichier>` : Ajoute un fichier spécifique à la staging area.
5. `git add .` : Ajoute tous les fichiers modifiés à la staging area.
6. `git commit -m "mon_message"` : Crée un commit (version) de votre code avec un message descriptif.
7. `git log` : Affiche l'historique des versions (commits) effectuées dans le dépôt.
8. `git log --oneline` : Affiche l'historique des versions sous forme condensée, avec chaque commit sur une seule ligne.
9. `git fetch` : Récupère les derniers changements du dépôt distant, met à jour les références locales mais ne fusionne pas les modifications avec la branche courante.
10. `git remote add origin <url_du_dépôt_distant>` : Lie le dépôt local au dépôt distant spécifié par l'URL.
11. `git remote set-url origin <url_du_dépôt_distant>` : Change l'URL du dépôt distant lié au dépôt local.
12. `git push origin <nom_de_la_branche>` : Envoie votre code dans le dépôt distant spécifié par la branche spécifiée.
13. `git checkout <nom_de_branche>` : Permet de basculer d'une branche à une autre dans votre dépôt.
14. `git checkout -b <nouvelle_branche>` : Crée une nouvelle branche et se positionne dessus simultanément.
15. `git merge <nom_de_branche>` : Fusionne la branche spécifiée avec la branche courante.
16. `git pull origin <branche>` : Récupère les derniers changements du dépôt distant dans la branche spécifiée et les fusionne avec la branche locale.
17. `git tag -a <tag_name> -m <message>` : Eg ; `git tag -a v1.0 -m"Version 1 lancé"`
18. `git tag -a <tag_name> <commit_id>` : Crée une étiquette (tag) pour le commit spécifié, permettant de marquer des versions ou des points spécifiques dans l'historique.
19. `git diff` : Affiche les différences non encore indexées (non ajoutées à la staging area) entre le dernier commit et le répertoire de travail.
20. `git diff <commit_id_1> <commit_id_2>` : Affiche les différences entre deux commits spécifiés.
21. `git revert <commit_id>` : Crée un nouveau commit qui annule les changements effectués dans le commit spécifié.
22. `git stash` : Met de côté les modifications locales non encore ajoutées au commit actuel, permettant de basculer entre les branches ou de travailler sur autre chose sans committer les changements en cours.
23. `git stash list` : Affiche la liste des stash (réserve) existants.
24. `git stash apply` : Applique le dernier stash sans le supprimer, permettant de récupérer les modifications mises de côté.
25. `git stash drop` : Supprime le dernier stash après l'avoir appliqué.
26. `git stash pop` : Applique le dernier stash et le supprime de la liste des stash.
27. `git reset <commit_id>` : Réinitialise la staging area et le répertoire de travail au commit spécifié.
28. `git reset --hard <commit_id>` : Réinitialise la staging area, le répertoire de travail et la branche courante au commit spécifié.
29. `git fetch --prune` : Récupère les derniers changements du dépôt distant et supprime les branches distantes obsolètes en local.
30. `git branch -d <nom_de_branche>` : Supprime la branche spécifiée localement après avoir fusionné ses changements.
31. `git branch -r -d origin/<nom_de_branche>` : Supprime la branche spécifiée à distance.

