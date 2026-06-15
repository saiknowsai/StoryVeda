# StoryVeda — AI Assistant Context

## Project Identity
**StoryVeda** — Children's Vedic storytelling website. Ancient wisdom through beautiful stories for ages 3-10.

## Working Directory
`C:\Users\sweth\Documents\StoryVedaLocal`

## File Structure
```
StoryVedaLocal/
├── index.html                    ← Homepage (age-filter layout, 6 story cards)
├── stories by age/
│   ├── 3-5/
│   │   ├── the-sun-wakes-up.html     ✅ Mantra · Gratitude
│   │   ├── the-sun-wakes-up/         (image folder, empty)
│   │   ├── why-the-river-sings.html  ✅ Nature · Creation
│   │   └── why-the-river-sings/      (image folder, empty)
│   ├── 6-8/
│   │   ├── the-boy-who-shared-his-last-roti.html  ✅ Values · Generosity
│   │   ├── the-boy-who-shared-his-last-roti/      (image folder, empty)
│   │   ├── prahlad-and-the-pillar-of-fire.html    ✅ Puranas · Faith
│   │   └── prahlad-and-the-pillar-of-fire/        (image folder, empty)
│   └── 9-10/
│       ├── arjunas-doubt.html       ✅ Mahabharata · Courage (with images)
│       ├── arjunas-doubt/           (2 scene JPEGs)
│       ├── king-harishchandras-promise.html  ✅ Values · Truth
│       └── king-harishchandras-promise/      (image folder, empty)
├── Arjunas-Doubt/                 ← Legacy image folder (keep for ref)
├── Sun-Wakes-Up/                  ← Legacy image folder (empty)
├── archive/                       ← Old versions preserved
├── NOTES.md
└── AGENTS.md
```

## Key Conventions
- Each story in its own age folder under `stories by age/`
- Each story has a matching image folder (e.g., `arjunas-doubt/` for `arjunas-doubt.html`)
- Story pages follow template: hero → scenes (with [Image: ...] placeholders) → quotes → value box → reflection → interactive quiz → nav
- Homepage sections: `#home`, `#why`, `#stories`, `#about`, `#connect`
- Story nav back-links: `../../index.html#stories`
- Subscribe link: `index.html#connect`

## Completed Stories (6/6)
1. **The Sun Wakes Up** — Mantra · ages 3-5 · Gayatri Mantra · gratitude
2. **Why the River Sings** — Nature · ages 3-5 · Ganga · creation
3. **The Boy Who Shared His Last Roti** — Values · ages 6-8 · generosity
4. **Prahlad and the Pillar of Fire** — Puranas · ages 6-8 · faith
5. **Arjuna's Doubt** — Mahabharata · ages 7-10 · courage (with 2 scene images)
6. **King Harishchandra's Promise** — Values · ages 8-10 · truth

## Notes
- Root-level `arjunas-doubt.html`, `sun-wakes-up.html`, `Arjunas-Doubt/`, `Sun-Wakes-Up/` are legacy — not linked from homepage anymore
- Original full index.html (with pillars, vedam, books) is in `archive/`
- User is in India, prefers free/low-cost tools
- Static HTML project (no build tools, no frameworks)
- Story pages use embedded CSS, no external stylesheets
