# Simple Flask Auth

Minimal Flask application with user registration and login using Bootstrap for the UI.

## Local Development

```bash
pip install -r requirements.txt
export FLASK_APP=app:create_app
flask run
```

This uses SQLite by default and stores data in `app.db`.

## Docker

Build and run the web app together with a Postgres database:

```bash
docker compose up --build
```

The site will be available at [http://localhost:5000](http://localhost:5000). The same `docker-compose.yml` can be used on a Linux server and exposed via a Cloudflared tunnel.
