# StoryVeda — Project Notes

## Project Structure

```
StoryVeda/
├── index.html              ← Homepage (was index3_OC.html)
│                              Clean layout with age filter tabs (3-5, 6-8, 9-10)
│                              Sections: Hero, Stories (with age filters), About, Connect
├── arjunas-doubt.html      ← Story page (was "arjunas-doubt - Copy.html")
│                              Enhanced version with:
│                              - Scene images from Arjunas-Doubt/
│                              - Interactive 5-question quiz
│                              - Krishna quotes, reflection prompts
├── Arjunas-Doubt/          ← Story images folder
│   ├── scene1-battlefield.jpeg
│   └── scene2-arjuna-doubt.jpeg
├── archive/                ← Old/duplicate files preserved here
│   ├── index.html          ← Original full-featured homepage (pillars, vedam, books, contact form)
│   ├── index1.html         ← Simpler sunrise hero variant
│   ├── arjunas-doubt.html  ← Original story page (emoji-only, no images/quiz)
│   ├── arjunas-doubt (1).html  ← Duplicate of original
│   └── body.html           ← HTML fragment with placeholder content + SVG
├── NOTES.md                ← This file
└── AGENTS.md               ← Session context for AI assistants
```

## Design Decisions

- **Homepage**: `index3_OC.html` (renamed to `index.html`) chosen as the canon homepage — clean age-filter layout, minimal sections, focused UX
- **Story page**: "arjunas-doubt - Copy.html" (renamed to `arjunas-doubt.html`) chosen over the original — it includes scene images and an interactive quiz
- **Original full index.html** preserved in `archive/` — the pillars/vedam/books sections can be split into separate microsites later
- **Images**: Each story gets its own folder (e.g., `Arjunas-Doubt/`)
- **Future stories** will follow the same page template structure

## File Sizes

| File | Size | Notes |
|------|------|-------|
| index.html | 23,401 B | Homepage (was index3_OC) |
| arjunas-doubt.html | 23,711 B | Story page (was - Copy) with quiz + images |
| scene1-battlefield.jpeg | 3.6 MB | Story image |
| scene2-arjuna-doubt.jpeg | 3.2 MB | Story image |

## Key HTML IDs (for linking)

- Homepage sections: `#home`, `#why`, `#stories`, `#about`, `#connect`
- Story page nav: `index.html#stories` (back link), `index.html#connect` (subscribe)

## Recent Changes

- Added "Why StoryVeda" section (#why) between Hero and Stories
  - Section tag: "Why it matters"
  - Title: "Vedic stories for a changing world"
  - 4 cards: Timeless Values, Gentle Learning, Family Moments, Trusted & Calm
  - Uses same warm, vibrant design language
- Updated nav to include "Why StoryVeda" link

## Tech Stack

- Static HTML + inline CSS + vanilla JS
- Google Fonts: Nunito, Playfair Display, Tiro Devanagari Sanskrit
- Hosting: GitHub Pages (user is on GitHub)
- No build tools, no frameworks — pure frontend

## Stories

| # | Story | Category | Ages | Status | File |
|---|-------|----------|------|--------|------|
| 1 | Arjuna's Doubt | Mahabharata | 7-10 | ✅ Live | `arjunas-doubt.html` |
| 2 | The Sun Wakes Up | Mantra | 3-6 | ✅ Live | `sun-wakes-up.html` |
| 3 | The Boy Who Shared His Last Roti | Values | 5-8 | ⏳ Pending | — |
| 4 | Prahlad and the Pillar of Fire | Puranas | 6-10 | ⏳ Pending | — |
| 5 | Why the River Sings | Nature | 4-7 | ⏳ Pending | — |
| 6 | King Harishchandra's Promise | Dharma | 8-10 | ⏳ Pending | — |

## Story Images Folders

- `Arjunas-Doubt/` — scene1-battlefield.jpeg, scene2-arjuna-doubt.jpeg
- `Sun-Wakes-Up/` — (empty, ready for images)

## Next Tasks

1. Write remaining 4 story pages
2. Add scene images to story folders
3. Deploy via GitHub Pages
