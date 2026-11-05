# Omkaresh R — White Dragon Portfolio

A static, GitHub Pages-ready portfolio built with HTML, CSS, and vanilla JavaScript. No npm install, build command, API key, or server is required.

## Visual structure
- Intro uses the supplied monochrome dragon emblem (`assets/dragon-intro-emblem.jpg`) with an animated reveal and 03 → 02 → 01 countdown.
- Home hero uses the supplied white dragon artwork (`assets/dragon-hero.jpg`).
- Six continuous scroll sections: Home, About, Work, Services, Tools, Contact.
- About is text-only (no portrait).
- Icy white/blue glass styling with restrained red accents.
- Responsive navigation, scroll reveal, ambient background graphics, animated tool tiles, and project filters.
- Local project images and videos are included in `assets/`.

## Publish to GitHub Pages
1. Extract the ZIP.
2. Upload the contents of this folder (the `index.html`, `README.md`, and `assets` folder) to the root of your GitHub repository.
3. Commit to the `main` branch.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.

## Notes
- Intro runs once per browser session. Refreshing after closing the tab will show it again; use the Skip intro button to bypass it.
- All icons are rendered with CSS/text marks; there are no external icon dependencies.
- Resume button opens an email request because no resume PDF was provided.
- Edit contact details and project titles directly in `index.html` if needed.


## Latest interaction update
- The intro emblem is displayed inside a circular crop with a layered neon ring.
- Removed the dragon sweep entirely from scroll events. Normal smooth scrolling and section reveal animations remain.
- Background ambient rings and app-tile hover animations provide motion without interrupting navigation.
