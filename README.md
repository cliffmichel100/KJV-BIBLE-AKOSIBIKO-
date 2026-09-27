# AkoSiBiko Bible Baptist KJV Study Bible

A free GitHub Pages-ready Bible study website. **Everything is at repository root level; there are no folders.**

## Upload to GitHub

Upload these files directly to your repository:

- `index.html`
- `README.md`

Then enable **Settings → Pages → Deploy from branch → main → / (root)**.

The site can be opened from the published GitHub Pages URL on phones, tablets and computers.

## What is included

- Physical-study-Bible inspired interface
- 66-book KJV navigation
- Chapter navigation
- Verse selection and study desk
- Search across books already cached in the browser
- Bible Baptist theological study framework
- Salvation and eternal-security lessons
- Local church, baptism, Lord's Supper, missions, separation and holiness lessons
- Discipleship lesson shelf
- Bible glossary and subject index
- Original schematic Bible maps
- Verse-level original study-note engine
- Local browser caching for opened Bible books
- No login and no server/database required

## KJV corpus

The application loads the 66-book KJV corpus from the public machine-readable `aruljohn/Bible-kjv` GitHub repository. That repository documents the 66 books as separate JSON files. Project Gutenberg also identifies its KJV edition as public domain in the United States.

Because GitHub Pages is a static host, the full KJV corpus is intentionally loaded on demand and cached in the browser instead of making the repository enormous. Opening all 66 books once gives the browser a local cached study library. A future fully self-contained/offline edition can bundle the 66 JSON files into one local `bible-data.js` file without changing the interface.

## Copyright / study-resource note

The site does **not** reproduce thousands of modern commercial commentaries. Instead, it provides original study notes, outlines, glossary material, verse-level study classification and a structure where the site owner can add properly licensed or public-domain resources. This is important when publishing a Bible study library publicly.

## Suggested expansion

You can add root-level files such as:

`strongs-lite.json`, `topics.json`, `crossrefs.json`, `lessons.json`, `people.json`, `places.json`, `maps.json`, `sermons.json`, `devotionals.json`, `memory-verses.json`.

The interface can then be extended to index those resources.
