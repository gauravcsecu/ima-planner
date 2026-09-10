IMA Study — GATE Multi-Stream v12

GitHub Pages / PWA ready.

NEW IN v12
- CS/DA Resources is read-only: no manual Add/Edit/Delete controls.
- Resources menu provides only Import Resources, Export Resources, and filters (Subject, Topic, Resource Type).
- Resource types: Complete Notes, Short Notes, 2–3 Slide Summary, MCQ, MSQ, Fill in the Blank.
- Imported notes can contain examples and images (images should be embedded as data URLs in the resource package).
- Imported question resources can contain multiple questions with answers and explanations.
- Resource imports MERGE into the existing CS/DA library and skip duplicates instead of replacing existing resources.
- Export Resources creates an IMA Study Resource Package JSON containing only CS/DA resources.
- Random Revision Pack uses imported resources.
- Missed Goals have explicit readable light/dark/night text and controls.

RESOURCE PACKAGE SCHEMA
{
  "app": "IMA Study Resource Package",
  "version": 2,
  "exam": "GATE",
  "branch": "CSDA",
  "resources": [
    {
      "id": "unique-id",
      "subject": "DBMS",
      "topic": "Normalization",
      "title": "Normalization — Complete Notes",
      "kind": "notes",
      "type": "complete_notes",
      "format": "complete_notes",
      "content": "# Normalization\n## 1NF\n...\nEXAMPLE: ...",
      "images": [{"src":"data:image/png;base64,...","caption":"Diagram"}]
    },
    {
      "id": "unique-id-2",
      "subject": "DBMS",
      "topic": "Normalization",
      "title": "Normalization PYQs",
      "kind": "questions",
      "type": "mcq",
      "questions": [{"type":"MCQ","q":"...","options":[{"key":"A","text":"..."}],"answer":"B","explain":"..."}]
    }
  ]
}

For GitHub updates: keep the same repository and GitHub Pages URL. Replace the website files with these files; do not clear browser/site storage.


V11 notes: Resource export respects the active Subject, Topic and Resource Type filters. This package contains no sample goals, sample notes, or sample resources.


V12 update: resource quiz interactions, local quiz/pack performance scoring, 5/10 MCQ or Short Notes revision-pack filter, and score reveal only after finishing.
