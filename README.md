Lors de notre projet, l'initialisation du projet "projet-equipe" a été faite par l'étudiant A (BITEGHE ISMAIL Hussein Haydar). Il a suite à ça créer le fichier index.html et l'a sauvegarder à l'intérieur du projet grâce aux commandes :
-git add . (pour ajouter dans la zone de transit)
-et git commit (pour ajouter dans le dépôt, reconnaissable par le message : Initialisation du projet equipe)
Enfin il a créé le dépôt sur GitHub et envoyer l'initialisation grâce aux commandes :
-git remote add origin 
-et git push -u origin main
L'étudiant B (MABIALA TOMO Ima-Kim Sergia) a cloné le projet de l'étudiant A, créé une branche et, à l'intérieur, créer un fichier style.css associer à l'index.html et envoyé les modification sur GitHub à l'aide de la commande : 
-git clone
-git add .
-git push origin
Pendant ce temps, l'étudiant A a créé une autre branche dans laquelle il a modifié le fichier index.html et et envoyé les modifications sur GitHub.
Puis il a fusionné sa branche à la branche principale (grâce à la commande git merge) et a récupéré la branche de l'étudiant B pour la fusionner (à l'aide des commandes "git fetch origin" puis "git merge origin"), également, à la branche principale. Puis a envoyer le tout sur GitHub (avec la commande git push).


