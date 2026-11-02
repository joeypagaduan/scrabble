# Scrabble Companion

A score keeper, turn timer, word checker, and head-to-head record book for games on a physical Scrabble board.

## Files

- `index.html` – the app
- `manifest.webmanifest`, `sw.js`, icons – let it install to an iPad home screen and run full screen, even offline
- `enable1.txt` – the word list (add this yourself, see below)

## Word list

Download `enable1.txt` (the free ENABLE word list, public domain) and upload it to this repo next to `index.html`.

## Updating the app

After changing `index.html`, open `sw.js` and bump `VERSION` (for example `scrabble-v2`) so iPads pick up the new version.

## Data

Scores and records are saved on each device. Use **Back up records** and **Restore backup** to move them between devices.
