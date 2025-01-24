Instller spotify depuis internet avec ce lien (ne marche pas avec le spotify du microsoft store): [ici](https://www.spotify.com/fr/download/windows/)

Une fois installé et connecté a votre compte spotify.
Ouvrir Windows PowerShell dans la barre de recherche windows (si la commande ne marche pas: executer en tant qu'administrateur).
Entrer les commandes suivante puis acceter avec [Y] (yes) ou appuyer sur entrer.
1ere commande :

iwr -useb https://raw.githubusercontent.com/spicetify/cli/main/install.ps1 | iex

2nde commande :
iwr -useb https://raw.githubusercontent.com/spicetify/marketplace/main/resources/install.ps1 | iex 

Pour les mises à jour :
spicetify update 
