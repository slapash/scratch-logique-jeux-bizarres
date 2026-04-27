# Générateur de logique Scratch — Jeux bizarres

Single-page French web app for kids/educators: choose a weird game idea and see the concept translated into Scratch-style logic blocks.

## Run locally

Open `index.html` directly, or serve it with:

```bash
python3 -m http.server 5179
```

Then visit `http://localhost:5179/`.

## Run with Docker

```bash
docker compose up --build -d
```

Then visit `http://localhost:5180/`.

Health check:

```bash
curl http://localhost:5180/health
```

## Stack

- Static HTML
- Tailwind CDN
- Alpine.js CDN
- Nginx container for deployment
- No build step
