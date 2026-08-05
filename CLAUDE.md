# Project notes for Claude

- This is a single static `index.html` file (student roster / Noto migration checklist) deployed via GitHub Pages.
- Student progress checkboxes are stored client-side only, in the browser's `localStorage` (`weo_sess` / `weo_stu` keys) — they are never part of the committed file. Use the built-in "Export progress" / "Import progress" buttons to move state between browsers/devices or as a backup.
- Standing instruction: after opening a PR against this repo, merge it automatically once it looks clean (no failing checks, no merge conflicts) — don't wait for explicit merge approval each time.

## Follow-ups

- **Rhea Sharma** — has real summer sessions in the Lesson Summary export (Bridge Program, 2 lessons since March) but is intentionally left out of the roster for now. Shaina asked to hold off until she has package/purchase info (parent account, purchased count) to add her with real numbers instead of a placeholder. Come back to this.
- **Elliott Blanchard** — package (Rachel Pauli's account) is labeled Bridge Program, but Shaina confirmed her actual sessions are booked as Launch Program. Package is mislabeled at the source — needs correcting in Noto/the billing system, not just here. Shaina flagged this as a minor FYI, not urgent.
- **Finn McGoldrick** — same issue: package (Bethany King's account) is labeled Roots Program, but his actual sessions are booked as Bridge Program. Also needs correcting at the source. Also just an FYI, not urgent.
- **Declan Quinn** — confirmed with Shaina that his parent (Amy Battista) genuinely has no package in the system yet. Needs one created in Noto; not a data-matching gap on our end.
- **Billy, Carolyn & Ryan Schultz** — share one family package under Jennifer Ryan (Bridge Program, 70 purchased). The purchased/used/remaining numbers shown for each of the three are the shared family total, not an individual balance per kid.
- **Lexie Bearce** — the Packages export has two conflicting/duplicate rows for her parent (Stephanie Crimmins: 22 Launch + 4 Bridge), neither matching Shaina's invoice. Used the invoice-confirmed number (10, Launch Program) combined with her actual lesson-log counts instead. Worth re-checking against Noto once that export is cleaned up.
- **Asher, Benjamin & Timothy Hung** — all three currently share one identical package under parent Isabel Hung (Launch Program, 12 purchased), same situation as the Schultz siblings, but this one hasn't been confirmed with Shaina yet as intentionally shared vs. a data gap where each kid should really have their own separate package. Come back to this.
- **Julian Rowan** — has a 4-pack purchased, but no real package balance/usage tracking exists for it yet. (An earlier pass had mismatched him to a "Sarah Nethercote" row from the Packages export — that was wrong and has been reverted; he now correctly shows "No package found" until real balance numbers exist.)
- **Ryan McCabe** — was showing a Jennifer McCabe / Launch Program package, but that wasn't really his: his actual sessions are College Launch work (lesson titles: "CL Essay", "CL #2", "CL #3", "CL #4") and Shaina can't find any College Launch invoice for him at all. Reverted to "No package found" rather than leave a package on his profile that isn't really his. This is a real gap, not just a labeling FYI — needs a package tracked down/created in Noto.
