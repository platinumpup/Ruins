RUINS PICKER PWA - v0.11

What it does:
- Shuffles numbers 1-20 into 3 Ruins categories:
  Main Spots: 4
  Substitute Spots: 8
  No Soup For You: 8
- Player list starts blank.
- Add players one at a time or paste a full list.
- Tap a number to replace it with a player.
- Lock a spot so Shuffle Unlocked leaves it alone.
- Tap a spot, choose Start Swap, then tap another spot to switch them.
- Copy Results gives a ready-to-send message.
- Player list and current board save automatically on the device.

New in v0.3:
- Compact Overlay Mode for Android floating-window testing.
- Narrow vertical layout.
- Bigger tap tiles in compact mode.
- Collapsible player list.
- Always-visible Copy Results button in compact mode.
- Glass/transparency slider for lighter or heavier card backgrounds.
- Cleaner in-app header with no logo inside the app.

Files:
- index.html: full app
- manifest.json: PWA install settings
- service-worker.js: offline caching
- icon-192.png and icon-512.png: original [OOF] Ruins PWA icons

To test locally:
1. Open the folder in VS Code.
2. Use Live Server, or run: python -m http.server 8000
3. Visit http://localhost:8000

Important:
Service workers usually need localhost or HTTPS. Opening index.html directly will show the app, but offline/PWA install may not fully work until hosted.

Android floating-window note:
The PWA cannot force itself to float above X-Clash. Use the phone/browser's floating window, pop-up view, or split-screen feature. Compact Overlay Mode is designed to fit better once the phone has made the browser/PWA window float.



v0.5 note: Compact Overlay Mode was rebuilt for narrow Android floating windows and service worker caching was changed to network-first for index.html.

v0.6 note: Splash screen and icons no longer use the X-Clash logo. It now shows “[OOF] OrganizedChaos”, “Loading Ruins Battlefield Picker...”, and a loading bar on a black neon-white splash screen.


v0.7 note: Splash animation changed from bounce/stomp to a drop-and-splat landing with a soft neon pulse. Compact Overlay Mode was forced tighter again: smaller header, hidden tagline/control title, denser cards, four-column tiles, collapsed player list, and fixed bottom Copy Results. Service worker cache bumped to v7. You can test compact directly with ?compact=1 at the end of the URL.


v0.8 note: Compact mode cleanup. Removed the glass slider, set a darker standard transparency, and changed Copy Results back into a normal full-width control so it no longer floats over or blocks other buttons. Service worker cache bumped to v8.


v0.11 note: Added a Light/Dark Mode toggle. Light mode keeps the same navy/green/berry/gold direction, but shifts it into a pale warm glass version so it can be previewed beside the darker look. The choice saves on the device.


v0.13: Unified picker control button typography so Reset Numbers and Clear Names match the other controls.
