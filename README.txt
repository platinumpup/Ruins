RUINS PICKER
[OOF] OrganizedChaos

Random chaos, precisely organized.

WHAT THIS IS
Ruins Picker is a simple offline-friendly PWA made for the X-Clash Ruins / Ruins Battlefield player-pick workflow.

It helps shuffle numbered spots into three groups:

- Main Spots: 4 picks
- Substitute Spots: 8 picks
- No Soup For You: 8 picks

The app is designed so the picker does not have to manually write out number swaps or replacement notes. She can add players locally, tap a number, replace it with a player, lock spots, shuffle unlocked spots, and copy the final results.

CORE FEATURES
- Shuffle numbers 1–20 into Ruins groups
- Shuffle all spots
- Shuffle unlocked spots only
- Lock all / unlock all
- Lock individual spots
- Replace a number with a saved player name
- Clear names without resetting the full board
- Reset numbers
- Add and remove players locally
- Player list saves on the device
- Saved roll history
- Purge saved rolls without deleting the player list
- Copy formatted results
- Light mode / dark mode
- Compact Overlay mode for Android floating-window testing
- PWA support for installing to home screen

PLAYER LIST
The player list starts blank.

Players are added directly inside the app and saved locally on the device/browser. This means the HTML does not need to be edited every time the union roster changes.

Saved players are stored separately from saved roll history.

PURGE SAVED ROLLS
The “purge saved rolls” link clears only saved roll history.

It does not delete:
- added players
- current board state
- light/dark preference
- compact mode preference

COMPACT OVERLAY MODE
Compact Overlay mode is designed for testing the app in Android floating-window or pop-up mode.

The PWA itself cannot force itself to float over X-Clash. The phone must support pop-up view, floating window, or split screen.

Recommended use:
1. Open X-Clash.
2. Open Ruins Picker.
3. Use the phone’s recent-apps menu to open Ruins Picker in pop-up/floating-window mode.
4. Turn on Compact Overlay inside Ruins Picker.

INSTALLING AS A PWA
On Android Chrome:
1. Open the GitHub Pages app link.
2. Tap the three-dot menu.
3. Tap Add to Home screen or Install app.
4. Open Ruins Picker from the home screen.

On desktop Chrome/Edge:
1. Open the GitHub Pages app link.
2. Use the install icon in the address bar, or browser menu.
3. Install as app.

GITHUB PAGES
This project is intended to run from GitHub Pages.

Expected repo:
https://github.com/platinumpup/Ruins

Expected Pages URL:
https://platinumpup.github.io/Ruins/

FILES
- index.html: main app
- manifest.json: PWA install settings
- service-worker.js: offline/cache support
- icon-192.png: app icon
- icon-512.png: app icon
- apple-touch-icon.png: iOS/home screen icon
- favicon-32.png: browser favicon
- favicon-64.png: browser favicon
- README.txt: project notes
- LICENSE.txt: license terms
- COPYRIGHT.txt: copyright and attribution notice

UPDATING THE APP
After editing files locally, push changes with:

cd "C:\Users\Sobaka\Desktop\Ruins"

git add .
git commit -m "Update Ruins Picker"
git pull --rebase origin main
git push origin main

If Git says there are conflicts, stop and resolve them before pushing.

CACHE NOTE
Because this is a PWA, GitHub Pages or the phone may keep showing an older cached version after updates.

If the app does not update:
- refresh the browser page
- clear site data for the Ruins page
- uninstall/reinstall the PWA
- make sure the service-worker cache name was changed in service-worker.js

NOTES
This is a fan-made utility for union organization.
It is not an official X-Clash app.
