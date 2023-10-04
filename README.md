# docker-compose
Gogs Un serviceauto-hébergé sans prise de tête

# Script pour télécharger docker et docker-compose
curl -fsSL https://get.docker.com | sh && sudo apt install -y docker-compose

# Création du dossier mystack

mkdir mystack

# Création du fichier docker-compose.yml

touch docker-compose.yml

# Lancement de la stack

docker-compose up - d

# Vérification du status up down ou exit

docker-compose ps

