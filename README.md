# Energy-Efficient Trot Gait for a Quadruped Rat Robot via Reinforcement Learning — Project Page

Static project page (GitHub Pages) for the master thesis. Built from the
[Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template)
(Nerfies-style, Bulma CSS).

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Publish on GitHub Pages

1. Create a new **empty** GitHub repo (no README), e.g. `rat-robot-thesis-page`.
2. Push this folder:
   ```bash
   git remote add origin https://github.com/ZSMandreas/rat-robot-thesis-page.git
   git branch -M main
   git push -u origin main
   ```
3. On GitHub: **Settings → Pages → Build and deployment → Deploy from a branch → `main` / `/ (root)`**.
4. The site goes live at `https://zsmandreas.github.io/rat-robot-thesis-page/`.

`.nojekyll` is included so GitHub Pages serves the `static/` assets unmodified.

## Editing

Open `index.html` and replace the placeholders: title, author/university, the three header
links (Thesis / arXiv / Code), and the BibTeX entry. Styling and assets are under `static/`.
