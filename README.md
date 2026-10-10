# Pick the Poop! — iPad Web App

This folder is ready for GitHub Pages. Upload the **contents** of this folder, not the enclosing folder. `index.html` must be at the repository root.

GitHub > New repository > `pick-the-poop-game` (Public) > Create > Add file > Upload files > select all files and the `icons` folder > Commit. If folder upload via browser is inconvenient, drag the `icons` folder into the upload area or upload all six files within it.

Settings > Pages > Deploy from a branch > main > /(root) > Save. Wait for your site to go live.

Open site on iPad **Safari** > Share > Add to Home Screen > Open as Web App (on) > Add.

## Notes
- Offline caching kicks in after the game is first loaded online.
- GitHub Pages site is publicly reachable. Avoid uploading private family photos or identifying details.
- Later updates should bump the cache version in `sw.js` when assets change.
- The app currently does not persist high scores between launches.
