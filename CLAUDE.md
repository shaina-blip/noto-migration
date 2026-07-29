# Project notes for Claude

- This is a single static `index.html` file (student roster / Noto migration checklist) deployed via GitHub Pages.
- Student progress checkboxes are stored client-side only, in the browser's `localStorage` (`weo_sess` / `weo_stu` keys) — they are never part of the committed file. Use the built-in "Export progress" / "Import progress" buttons to move state between browsers/devices or as a backup.
- Standing instruction: after opening a PR against this repo, merge it automatically once it looks clean (no failing checks, no merge conflicts) — don't wait for explicit merge approval each time.
