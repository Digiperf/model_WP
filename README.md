<h1>Installation</h1>

1. Lancer l'installation du conteneur docker avec les configs présentes dans `docker-compose.yml`
2. Si besoin d'éteindre le conteneur : `docker compose down -v`
3. Si modif du `docker-compose.yml`, on relance l'installation avec `docker compose build --no-cache`
4. On le remonte avec `docker compose up -d`
5. Pour accéder au conteneur : `docker exec -ti test-wordpress-1 bash`

<h1>Configuration</h1>

- Créer un fichier `.env` avec les bons credentials de staging ou de prod

<h1>Tools</h1>

- `wp-cli`est installé dans le dossier `/tools` est est accessible avec la commande `php wp-cli.phar options`
- `Makefile`est installé par défaut