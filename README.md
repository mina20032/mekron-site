# MEKRON — AI Automation Solutions (Static Site)

A clean, fast static landing page built from your presentation.

## Structure
```
mekron-site/
├── index.html
├── styles.css
└── assets/
    └── mekron-logo.png
```

## How to Run Locally
1. Open the folder in VS Code.
2. Use a simple HTTP server:
   - Python: `python -m http.server 8080`
   - Node: `npx serve`
3. Visit http://localhost:8080

## Deploy to GitHub + Vercel
1. Create a new GitHub repo (e.g., `mekron-site`).
2. Push the folder:
   ```bash
   cd mekron-site
   git init
   git add .
   git commit -m "MEKRON static site v1"
   git branch -M main
   git remote add origin <YOUR_REPO_URL>
   git push -u origin main
   ```
3. Go to Vercel → **New Project** → import the repo.
4. Framework preset: **Other** (static).
5. Build command: **None**
6. Output directory: **/** (root)
7. Deploy.

## Customize
- Update hero text or sections directly in `index.html`.
- Replace `assets/mekron-logo.png` with any logo (same name) to change the branding.
- Colors are in CSS variables at the top of `styles.css`.

© 2025 MEKRON
