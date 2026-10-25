# Creeves Arcade 🕹️

One repository, many small games. The home page (`index.html`) is the arcade cabinet — it links to every game, and each game lives in its own folder as a single self-contained page. No build steps, no dependencies; everything runs in the browser.

## Games

| Game | Folder | What it is |
| --- | --- | --- |
| 🍙 Spam Musubi Stand | [`spam-musubi-game/`](spam-musubi-game/) | A 2-minute lunch rush: build musubi to order, time the sear, beat the clock. |
| 🚚 Mail Truck Flip | [`mail-truck-flip/`](mail-truck-flip/) | Slingshot a mail truck off a ramp and flip it — packages fly, landings get judged. |
| 🏝️ Tropical Island Builder | [`tropical-island-builder/`](tropical-island-builder/) | A tiny SimCity on a tropical island: build with shells, grow population and tourism, weather the storms. |
| 🏄 Wave Rider | [`wave-rider/`](wave-rider/) | Endless surfing: ride the wave, keep your balance, chain tricks for combos. |

## Play online

With GitHub Pages enabled for this repo (Settings → Pages → deploy from the `main` branch, root folder), the arcade is live at:

**https://creevesu.github.io/Creevesu2/**

Each game gets its own link too, e.g. `https://creevesu.github.io/Creevesu2/spam-musubi-game/`.

## Adding a game

1. Put the game's page in its own folder: `<game-name>/index.html`.
2. Add a card for it in the root `index.html` linking to `./<game-name>/`.
3. Add a row to the table above.

That's it — the arcade page and GitHub Pages pick it up automatically.
