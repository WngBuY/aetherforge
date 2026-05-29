# AetherForge

**AetherForge** is an AI agent platform — one place to design, orchestrate, and
deploy multi-model AI agents, from quantitative trading to automated content
creation.

This repository contains the marketing landing page for the product, built as a
single static HTML file and hosted on **GitHub Pages**.

## Use cases

- **AI Quantitative Trading Agents** — agents that ingest market data, evaluate signals, and execute strategies within defined guardrails.
- **Automated Content Creation** — research → draft → review pipelines that turn briefs into on-brand assets at scale.
- **Multi-Model Agent Orchestration** — coordinate specialized agents across providers, routing each step to the best-suited model.

## Project structure

```
.
├── index.html   # Single-page site (HTML + CSS + a little JS, no build step)
└── README.md
```

There is **no build step and no dependencies** — everything is inlined in
`index.html`, so the page works the moment it is served.

## Run locally

Just open the file in a browser:

```bash
# macOS
open index.html
# Windows
start index.html
```

Or serve it with any static server, e.g.:

```bash
python -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select branch `main` and folder `/ (root)`, then **Save**.
5. Wait ~1 minute; your site goes live at
   `https://<username>.github.io/<repository>/`.

## Contact

contact@aetherforge.bond
