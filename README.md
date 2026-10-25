# Discover Resorts — Room Command Center (JavaScript)

A deploy-ready static website built with **HTML, CSS, and vanilla JavaScript**. No React, Node.js, npm, bundler, server, API key, or environment variables are required.

## Project structure

```text
discover-resorts-room-command-center-js/
├── index.html
├── src/
│   ├── styles.css
│   └── app.js
├── README.md
├── .gitignore
└── LICENSE
```

## Run locally

Open `index.html` in any modern browser. For a local server, use VS Code Live Server, or run:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a repository on GitHub.
2. Upload the **contents** of this folder so `index.html` is at the repository root.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for the deployment status to become active; open the URL shown in Pages.

All project asset paths are relative (`./src/...`), so the site works from a GitHub Pages project URL, not just a custom domain.

## Features

- Responsive dark hacker-style interface.
- Room categories and YouTube room videos.
- Offer tariff table and copy-offer action.
- Daily activity calendar for October 2026.
- Copy room and daily activity details.
- No inline JavaScript event handlers; interactions use delegated event listeners.
- Clipboard API with fallback for browsers where clipboard access is restricted.

## Before publishing

Review all tariffs, policies, video links and the offer validity. The supplied content states the Eat4Free offer is valid from 11–20 October 2026.
