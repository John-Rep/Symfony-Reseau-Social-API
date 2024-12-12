Guide d'installation

Il faut suivre ce guide après avoir téléchargé le projet réseau social de base, si vous ne l'avez pas fait, vous pouvez le trouver au lien suivant:
https://github.com/John-Rep/Symfony-Reseau-Social

Clonez le repository en local avec la commande:
  git clone https://github.com/John-Rep/Symfony-Reseau-Social-API.git

Si vous avez changé le port dans le projet de base, il faut changé le port encore dans le fichier .env de ce projet pour connecter à la même base de données

Et maintenant il faut juste démarrer le serveur avec la commande: Symfony server:start

Si vous allez à l'URL http://localhost:8000/api, il doit afficher l'API où vous pouvez gérer les utilisateurs du site web
  Si vous avez démarré ce projet en même temps que le réseau social de base, il est probable que le port soit 8001 et pas 8000.
