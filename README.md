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

## Racing together

Both of you open the game from the same link (the home-screen icon is best).

1. One person taps **Play together → Host a race**. A 4-letter code appears.
2. The other taps **Play together → Join a race** and types the code.
3. The person joining picks a racer and kart, then taps **Ready!**
4. The host picks their own racer, then chooses **Free Race** or **Grand Prix** (Heart Cup, Star Cup or the harder Crown Cup) and a track, and taps **Race!**

You race each other plus six AI drivers. The host chooses what happens after each race. The
connection goes straight from one phone to the other. It's most reliable when both phones
are on the same Wi-Fi. If joining fails on mobile data, switch both to Wi-Fi and try again.

## Updating

Upload the changed files to the same repository. The game checks for a new version whenever it
opens with an internet connection. After the first visit it also works offline.

## Files

- `index.html`: the game
- `three.min.js`: the 3D engine (three.js r158, MIT licence)
- `peerjs.min.js`: connects the two phones for racing together (PeerJS 1.5.5, MIT licence)
- `manifest.webmanifest`, `sw.js`, `icon-*.png`, `apple-touch-icon.png`: tell phones how to install and run it full screen, and keep it working offline
