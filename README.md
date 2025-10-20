# Docker Dev Environment
Repo avec la mise à disposition d'environnements de test et de développement basé sur Docker.

### Web Dev PHP
Copier les sources de webdev-php dans le répertoire du projet 
```
docker compose up --detach
```
Connexion base SQL en CLI
```
docker exec -it postgresql psql -U my_user -d database_project
```

Accès à mailpit sur le port 8025.