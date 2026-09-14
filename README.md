# IMA Study — GATE 2027 · v23

GitHub Pages / PWA release.

## v23 UI update
- Replaced the Premium Color 1–10 text list with visual color swatches.
- Removed the repeated Add subject controls from every month/week.
- Added one planning control below Subject Short Forms: Select Month → Select Week → Select Subject Short Form → Add to Plan.
- Only months containing at least one planned subject are shown.
- Month Wise and Month Wise · Week Wise views remain available.
- Existing branch-local study data and Monthly Plan data remain compatible.

## Included files
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- icon-512-maskable.png
- README.md
- README.txt

## GitHub Pages update
Replace all existing repository files with all 8 files from this release. Do not upload only `index.html` because the PWA manifest and service worker also need to be updated.

After committing, open the GitHub Pages site URL, not the GitHub file viewer. If an installed PWA still shows an older screen, close it and reload the Pages URL so the v23 service worker can replace older IMA Study caches.


v23 UI update: improved mobile Full form / Short form alignment and stronger light-theme contrast for Import/Export resource controls.


## v23
- Added custom course setup for Other Exam and GATE Other Branch.
- Custom courses use separate local storage and start with an empty syllabus.
- Monthly Plan subject short forms increased to 30.
- Subject colors are assigned automatically and kept unique.
