# Escape-Game
Récupérer le fichier escape_game sous github : git clone github.com/Anais5s/Escape-Game. <br />
<br />
Dans un terminal, lancer l’exécution du fichier setup.sh (attention à activer les droits d’administrateur
avec chmod u+x setup.sh, et de même pour le fichier restart.sh à utiliser si l’on souhaite relancer le
jeu). Cela mènera au lancement du mini-jeu.<br />
Le dossier contient à présent 5 éléments :<br />
• cadenas.sh<br />
• game_files<br />
• restart.sh<br />
• setup.sh<br />
• setup.sh.save<br />
<br />
L’objectif du jeu est de déverrouiller le cadenas. Pour cela, il faut obtenir un code à 3 chiffres. Chaque
chiffre sera donné par la résolution d’un problème.<br />
Aller dans le répertoire game_files. Dans ce dossier se trouvent trois sous-dossiers : 1er_chiffre,
2eme_chiffre, 3eme_chiffre.<br />
Chacun d’eux contient un fichier Instructions qui indique ce qu’il faut faire pour révéler chaque chiffre.<br />
Attention, pour les chiffres 2 et 3, veuillez lancer les scripts verification.sh afin d’obtenir le chiffre
correspondant.<br />
1er chiffre : identifier un fichier d’une certaine taille et l’ouvrir<br />
2eme chiffre : modifier les droits d’accès/modification du fichier<br />
3eme chiffre : créer un sous-répertoire et y copier un fichier<br />

Une fois les 3 chiffres révélés, revenir dans le dossier principal pour lancer le fichier cadenas.sh.<br />
Rentrer le code et si tout s’est bien passé vous êtes libre !
