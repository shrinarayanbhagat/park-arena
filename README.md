# Park Arena — Smart Parking in Bhopal

A single-page website for Park Arena, a smart parking concept for Bhopal, built with Tailwind CSS and Leaflet.js (for the interactive map).

## 🚀 How to publish this on GitHub Pages

1. **Create a new repository** on GitHub (e.g. `park-arena`).
2. **Upload the files** in this folder to the repo:
   - `index.html`
   - `README.md` (optional, but nice to keep)

   You can do this via the GitHub web UI ("Add file" → "Upload files") or with git:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Park Arena site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/park-arena.git
   git push -u origin main
   ```
3. **Enable GitHub Pages**:
   - Go to your repo → **Settings** → **Pages**
   - Under "Build and deployment", set **Source** to `Deploy from a branch`
   - Choose branch `main` and folder `/ (root)`
   - Click **Save**
4. Wait a minute or two — GitHub will give you a live URL like:
   ```
   https://<your-username>.github.io/park-arena/
   ```

That's it — no build step needed, since this is a static HTML file with CDN-hosted dependencies (Tailwind CSS and Leaflet.js).

## 🗂️ Project structure

```
park-arena-site/
├── index.html   # The entire website (HTML + CSS + JS in one file)
└── README.md    # This file
```

## 🛠️ Notes

- The page uses Tailwind CSS via CDN and Leaflet.js for the map — no local build tools or `npm install` required.
- Since everything is self-contained in `index.html`, you can also just double-click the file to preview it locally in your browser before publishing.