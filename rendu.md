# I. Mise en place du lab

## 1. Création des réseaux
création des carte reseaux host only avec les bonnes ip
## 2. Création des VMs
création des 3 vm : 1 client, 2 server et un routeur.
## 3. Mise en place du routage statique
Le but ici est que chaque VM puisse se ping en créant un réseau.
Apres avoir definis les IPs statiques, definis les noms de domaine ainsi que remplis les fichiers /ect/hosts avec les nom de domaines et IPs des 2 autres VM.
Apres tout cela fait, il ne reste juste qu'à rentrer la commande `ping "nom de domaine de l'autre vm"`
voici un exemple : ![](https://github.com/GratinDauphinoi/CCNA_tp4/blob/master/all_ping.PNG?raw=true)