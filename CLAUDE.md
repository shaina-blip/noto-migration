# Project notes for Claude

- This is a single static `index.html` file (student roster / Noto migration checklist) deployed via GitHub Pages.
- Student progress checkboxes are stored client-side only, in the browser's `localStorage` (`weo_sess` / `weo_stu` keys) — they are never part of the committed file. Use the built-in "Export progress" / "Import progress" buttons to move state between browsers/devices or as a backup.
- Standing instruction: after opening a PR against this repo, merge it automatically once it looks clean (no failing checks, no merge conflicts) — don't wait for explicit merge approval each time.

## Follow-ups

- **Rhea Sharma** — has real summer sessions in the Lesson Summary export (Bridge Program, 2 lessons since March) but is intentionally left out of the roster for now. Shaina asked to hold off until she has package/purchase info (parent account, purchased count) to add her with real numbers instead of a placeholder. Come back to this.
- **Elliott Blanchard** — package (Rachel Pauli's account) is labeled Bridge Program, but Shaina confirmed his actual sessions are booked as Launch Program. Package is mislabeled at the source — needs correcting in Noto/the billing system, not just here.
- **Finn McGoldrick** — same issue: package (Bethany King's account) is labeled Roots Program, but his actual sessions are booked as Bridge Program. Also needs correcting at the source.
- **Declan Quinn** — confirmed with Shaina that his parent (Amy Battista) genuinely has no package in the system yet. Needs one created in Noto; not a data-matching gap on our end.
- **Billy, Carolyn & Ryan Schultz** — share one family package under Jennifer Ryan (Bridge Program, 70 purchased). The purchased/used/remaining numbers shown for each of the three are the shared family total, not an individual balance per kid.
- **Lexie Bearce** — the Packages export has two conflicting/duplicate rows for her parent (Stephanie Crimmins: 22 Launch + 4 Bridge), neither matching Shaina's invoice. Used the invoice-confirmed number (10, Launch Program) combined with her actual lesson-log counts instead. Worth re-checking against Noto once that export is cleaned up.
