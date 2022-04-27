#e2295393 Vincent Dubois
Activité 8
Première étape:

Initialiser le dépôt au nom username.github.io pour pouvoir l'héberger.

Renommer votre dépôt distant du tp2 de sorte qu'il s'intitule TP2.
Initialiser votre dépôt distant au nom username.github.io (comme au TP2)
Cloner votre dépôt distant sur votre poste locale et l'ouvrir dans VS Code.
Créer une page web simple avec en titre Activité 8, avec un bouton.
Versionner(commit).
Deuxième étape:

Configurer Live Server dans VS Code en utilisant le bon paramétrage.

Installer l'extension Live Server.
Installer l'extension Debugger for Chrome (Nightly)
Modifier le paramètre «host» pour que sa valeur soit «localhost».
Modifier le settings.json pour assigner le port par défaut à: 8080.
Créer ou copier le launch.json dans le dossier .vscode de votre dépôt local.
Appuyer sur Go Live, votre page Web devrait apparaître.
Appuyer sur F5 pour vérifier si tout fonctionne. (Si c'est le cas, vous devriez voir votre page HTML une deuxième fois).
Vous pouvez appuyer sur le carré dans VS Code (en haut, dans la barre de débogage).
Placer VS Code et Chrome côte à côte.
Écrire le sous-titre suivant: Apprendre à déboguer! et sauvegarder.
Observer le résultat.
Troisième étape:

Initialisation au déboguage et à console.log()

Consulté le site publier sur le site du court (point de départ pour l'activité).
À l'aide de l'outil de développement de votre navigateur Web (ctrl+shift+i), observer l'implémentation des boutons.
Modifier l'implémentation de votre page HTML de sorte que le bouton lance 3 messages:
Un message normal qui indique: Message //Versionner ici
Un message de type warning qui indique: Attention! //Versionner encore
Un message de type erreur qui indique: ERREUR //Versionner une autre fois
Placer un breakpoint dans votre code de sorte que l'exécution arrête avant l'affichage du message d'erreur(ERREUR). Prendre une prise d'écran.
Lancer l'exécution avec F5 et prendre une prise d'écran avec seulement le Message et le Attention! à la console.
