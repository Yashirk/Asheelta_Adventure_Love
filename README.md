# Asheelta_Adventure_Love
# Nichel ♥ Asheelta — The Short Love Quest

A short, self-contained pixel-art platformer made for mobile browsers. It uses HTML Canvas and inline JavaScript/CSS; there are no game-engine or asset downloads required.

## Play locally

Open `index.html` in a modern desktop browser. For the best phone experience, host it with GitHub Pages and open the resulting HTTPS link on the phone.

## Controls

- Mobile: hold the left/right buttons to move; tap Jump, Dash, or Attack.
- Keyboard: A/D or arrow keys to move, Space/W/Up to jump, Shift/K to dash, J/X to attack, Escape/P to pause.
- The pause button is in the top-right corner during gameplay.

## Game path

1. Green Kingdom
2. Cursed Forest
3. Heartbreaker Dragon
4. Exact custom confession for Asheelta
5. “Yes” and “YES!!!” both lead to the happy celebration ending

Roses, hearts, temporary shields, speed boosts, enemies, spikes, saws, fire vents, moving/crumbling platforms, treasure chests, a checkpoint system, dragon projectiles and a boss health bar are included.

## Publish it for Asheelta (free with GitHub Pages)

1. Create a GitHub repository (for example `nichel-love-quest`).
2. Upload `index.html`, `manifest.json` and `README.md` from this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/(root)`, and save.
5. Once GitHub Pages is published, open its HTTPS URL on your phone and send that link to Asheelta. She won't need to install an app or download anything.

The included manifest is a convenience for browsers that offer “Add to Home Screen”; it is not required to play.


## Fullscreen

Tap **⛶ Fullscreen** at the top of the game. On browsers that support it, the game uses the native Fullscreen API and requests landscape orientation where permitted. If document fullscreen is unavailable (for example, in some iPhone browser versions), it switches to an edge-to-edge immersive layout instead. Tap **Exit Fullscreen** to return. Browser UI may remain visible in the fallback mode.
