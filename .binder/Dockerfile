FROM gcc:latest

# Installer un éditeur/terminal basique
RUN apt-get update && apt-get install -y build-essential

# Définir le répertoire de travail
WORKDIR /home/jovyan

# Copier les fichiers du dépôt
COPY . .

# Commande par défaut : compiler puis exécuter main.c
CMD gcc main.c -o main && ./main
