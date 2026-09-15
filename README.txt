# IMA Study — GATE 2027 · v24

GitHub Pages / PWA release.

## v24 update
- Resource Library now imports and exports visual ZIP packages.
- Resource ZIP contains `resource.json` plus local `images/` files.
- Complete Notes, Short Notes, Slides, MCQs, MSQs and FIB resources can display local images.
- Diagram/question images and explanation images are supported in quiz cards.
- Added a dedicated PYQ Library menu with ZIP import/export.
- PYQ ZIP contains `pyq.json` plus local `images/` files.
- Imported images are converted to local data URLs and remain available offline.
- Exported resources/PYQs rebuild image files into the ZIP.
- Missed Goals now use a dark-blue high-contrast background for dark mode readability.
- Existing GATE branches, custom courses, Monthly Plan and 30 automatic-color subject tags are preserved.

## Visual resource package format
Resource ZIP:
- `resource.json`
- `images/...`

Use image paths such as `images/er-model.png` in resource `images`, slide `images`, question `image`/`images`, or explanation image fields. IMA Study resolves them locally on import.

## PYQ package format
PYQ ZIP:
- `pyq.json`
- `images/...`

`pyq.json` contains a `pyqs` array. A PYQ can contain `image`, `images`, `explainImage`, or `explainImages` using paths inside the ZIP.

All study data remains local in the browser.
