# Fridgey 🧊

A cute little tracker for what's in your fridge, shelf and cabinet. One HTML file, no account, and **all data stays on your device** (browser localStorage).

## Put it on your iPhone
1. Host this folder anywhere static (GitHub Pages works well) and open the URL in **Safari**.
2. Tap **Share → Add to Home Screen**.
3. Open it from the home-screen icon. It runs full screen and works offline.

> Data lives inside the home-screen app. Export a backup now and then (⚙️ → Export backup).

## How to use
- **+**: add food. Typing `鸡蛋 x6` sets the count, and the emoji and type are guessed for you. **Add & next** keeps the sheet open so you can put away a whole grocery run.
- **Tap the amount pill** to use some (Full → Most → Half → Low → finished).
- **Swipe right**: finished, with a one-tap "+ List". **Swipe left**: delete. Both can be undone.
- **Hold** a row to multi-select, then Move, mark Opened, or Delete.
- **Eat soon** at the top shows anything expiring within 3 days or flagged "Use soon".
- **Shopping**: tick items as you buy them, then **Put away →** stocks them in one step. "Maybe buy" suggests low and recently finished items.
- ⚙️ **Settings**: rename or reorder places and types, export/import a backup, or copy the list as text.

## Run locally
```bash
python3 -m http.server 5173
```
