# Cuutie Kart: home-screen version

This folder is the whole game. Put it on any website that uses https and it can be
added to a phone's home screen. From there it opens full screen, like an app.

## Put it online with GitHub Pages (free)

1. Sign in at github.com and create a new **public** repository, for example `cuutie-kart`.
2. On the repository page, choose **Add file > Upload files**. Drag in every file from
   this folder (not the folder itself), then press **Commit changes**.
3. Go to **Settings > Pages**. Under "Build and deployment", set Source to
   **Deploy from a branch**, pick the **main** branch and the **/ (root)** folder, and press **Save**.
4. After a minute or two the page shows your link, for example
   `https://YOUR-NAME.github.io/cuutie-kart/`.

Netlify Drop (app.netlify.com/drop) works too: drag this folder onto the page.

## Install it on a phone

**iPhone or iPad (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
Start the game from the new icon to get full screen.

**Android (Chrome):** open the link, tap the **three-dot menu**, then **Add to Home screen** or
**Install app**. The installed game opens full screen in landscape. In a normal Chrome
tab you can also press the **Full screen** button on the title screen.

## Updating

Upload the changed files to the same repository. The game checks for a new version whenever it
opens with an internet connection. After the first visit it also works offline.

## Files

- `index.html`: the game
- `three.min.js`: the 3D engine (three.js r158, MIT licence)
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png`: tell phones how to install and run it full screen, and keep it working offline
