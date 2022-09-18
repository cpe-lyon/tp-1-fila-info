Manuel

1. La commande “which”: localise une commande, un binaire dans le shell.
2. /search option
3. On quitte avec la touche “q”
4.

Navigation dans l’arborescence des fichiers

1.<img width="367" alt="image" src="https://user-images.githubusercontent.com/97104312/190902954-16794408-a6a5-4706-bb51-fd30187b8344.png">

2.<img width="353" alt="image" src="https://user-images.githubusercontent.com/97104312/190902969-f4eba63b-c5e0-49ae-b5a2-2fd5113e9d42.png">

3.<img width="349" alt="image" src="https://user-images.githubusercontent.com/97104312/190903001-99c33d68-90b0-4615-af3c-60b813d16f7a.png">

4.<img width="302" alt="image" src="https://user-images.githubusercontent.com/97104312/190903018-37c4cd5b-3ec9-420c-8776-a557dcea7e01.png">

5.<img width="432" alt="image" src="https://user-images.githubusercontent.com/97104312/190903050-5c38ddae-059c-48d3-9284-c14102bf52a2.png">

6.<img width="834" alt="image" src="https://user-images.githubusercontent.com/97104312/190903127-4aac4909-9077-4ec6-af47-ea3897d3a142.png">
La commande cd ne peut être utilisée directement avec la commande sudo.

7.<img width="830" alt="image" src="https://user-images.githubusercontent.com/97104312/190903191-cb024dbb-40d3-4c81-bba2-3d0bf5a37923.png">

8.<img width="768" alt="image" src="https://user-images.githubusercontent.com/97104312/190903204-1657cd05-b3e3-4311-8339-65fa39ce5478.png">
Le fichier “Fichier1.txt” ne peut être supprimé avec seulement “rm Fichier1.txt” il faut précéder de la commande “sudo”

9.La commande “rm” permet de supprimer un dossier

10.<img width="514" alt="image" src="https://user-images.githubusercontent.com/97104312/190903225-7b068ff0-7457-4fe6-9298-0d4bb55205a6.png">
La commande “rm” ne peut supprimer un répertoire.

11. Avec la commande “rm -rf Dossier2”

Commandes importantes
1.La commande “date” permet d’afficher l’heure.
   La commande “time” permet de lancer un chronomètre.
2.”Ls” et “La” sert à montrer les contenus d’un répertoire, pendant que “ls” est la commande pour faire ceci, “la” est une alias de cette commande.

3.<img width="307" alt="image" src="https://user-images.githubusercontent.com/97104312/190903279-c634de9a-e78f-45d1-9c3f-37df1e294222.png">
Le programme ls se trouve à /usr/bin/ls

4. ”ll” est l’alias de la commande “ls -alF”

5. “ls /bin”  

6. La commande “ls ..” permet de montrer les contenus du dossier parent.

7.”pwd” donne le chemin complet du dossier courant.

8.Écrase le contenu du fichier pour écrire bip

9.Ajoute le mot plop a la suite des mots du fichier

10. Cette commande affiche “toto” dans la commande line puis attendre 10sec.

11. La commande file affiche le type d’un fichier/répertoire.

12.”touch original.txt”
     “sudo nano original.txt” écrire “Hello Toto !” et enregistrer.
<img width="846" alt="image" src="https://user-images.githubusercontent.com/97104312/190903401-6a29e741-c5a3-4944-8227-977e7d0a9b64.png">

13. lien_sym contient le contenu de lien_phy et sa modification
<img width="355" alt="image" src="https://user-images.githubusercontent.com/97104312/190903584-c78b82e0-7b67-42b9-98ae-2ed8a7f107c6.png">
Après la suppression de lien_phy, lien_sym contient le dernier contenu de lien_phy.

14. Crtl + C permet d’arrêter le défilement.

15.
Afficher les 5 premières lignes:
	“head -5 syslog”
Afficher les 15 dernières lignes:
	“tail -15 syslog”
Afficher seulement les lignes 10 à 20:
	“head -20 syslog | tail +10”

16. La commande permet de lire le buffer.

17. Le fichier contient les noms d'utilisateurs.
	“man passwd ”’afficher la page de manuel de ce fichier

18. “cat etc/passwd | sed 's/\:/ /'|awk '{print $1} | sort | tac”

19. getent passwd | wc -l    il existe 34 utilisateur

20. <img width="431" alt="image" src="https://user-images.githubusercontent.com/97104312/190903718-73bd655e-b9df-4f64-994d-f34d8e96b66c.png">

21. <img width="374" alt="image" src="https://user-images.githubusercontent.com/97104312/190903734-489df8c7-0304-474f-813c-acdf629342bd.png">

22.find / -name passwd > ~/list_passwd_files.txt i2> /dev/null
<img width="635" alt="image" src="https://user-images.githubusercontent.com/97104312/190903759-8c2639e8-a9c1-473d-b9cc-49f25d15ca5e.png">


