# StoryVeda — Project Notes

## Live Site
`https://saiknowsai.github.io/StoryVeda/`

## Project Structure
```
StoryVedaLocal/
├── index.html                    ← Homepage (age-filter layout, warm saffron theme)
├── stories by age/
│   ├── 3-5/
│   │   ├── the-sun-wakes-up.html     ✅ Live
│   │   ├── the-sun-wakes-up/         (6 images)
│   │   ├── why-the-river-sings.html  ⏳ Coming Soon
│   │   └── why-the-river-sings/      (prompts only)
│   ├── 6-8/
│   │   ├── the-boy-who-shared-his-last-roti.html  ⏳ Coming Soon
│   │   ├── the-boy-who-shared-his-last-roti/      (prompts only)
│   │   ├── prahlad-and-the-pillar-of-fire.html    ⏳ Coming Soon
│   │   └── prahlad-and-the-pillar-of-fire/        (prompts only)
│   └── 9-10/
│       ├── arjunas-doubt.html       ✅ Live
│       ├── arjunas-doubt/           (5 images + prompts)
│       ├── king-harishchandras-promise.html  ⏳ Coming Soon
│       └── king-harishchandras-promise/      (prompts only)
├── archive/                       ← Old versions preserved
├── .gitignore
├── NOTES.md
└── AGENTS.md
```

## Design Decisions
- **Colour themes per story**: Each story page has its own embedded CSS colour palette
- **Sun Wakes Up**: Pinkish-yellow sunrise palette (rose/coral/gold) — light backgrounds so images pop
- **Arjuna's Doubt**: Deep purple/gold cinematic palette
- **Images**: Generated via Google Flow, stored in story's image folder, referenced with relative paths
- **Text under images**: Enlarged font (1.05rem) for important dialogue placed inside story-moment divs
- **Homepage**: Only Sun and Arjuna are clickable; 4 others show "Coming Soon" badge

## Tech Stack
- Static HTML + inline CSS + vanilla JS
- Google Fonts: Nunito, Playfair Display, Tiro Devanagari Sanskrit
- Hosting: GitHub Pages (public repo)
- Images: Google Flow (Nano Banana / Imagen 4)
- No build tools, no frameworks — pure frontend

## Stories

| # | Story | Category | Ages | Status | Notes |
|---|-------|----------|------|--------|-------|
| 1 | The Sun Wakes Up | Mantra | 3-6 | ✅ Live | 6 images, pinkish-yellow theme |
| 2 | Why the River Sings | Nature | 4-7 | ⏳ Coming Soon | Prompts ready |
| 3 | The Boy Who Shared His Last Roti | Values | 5-8 | ⏳ Coming Soon | Prompts ready |
| 4 | Prahlad and the Pillar of Fire | Puranas | 6-10 | ⏳ Coming Soon | Prompts ready |
| 5 | Arjuna's Doubt | Mahabharata | 7-10 | ✅ Live | 5 images, cinematic theme |
| 6 | King Harishchandra's Promise | Dharma | 8-10 | ⏳ Coming Soon | Prompts ready |

## Key HTML IDs (for linking)
- Homepage sections: `#home`, `#why`, `#stories`, `#about`, `#connect`
- Story page nav: `../../index.html#stories` (back link), `../../index.html#connect` (subscribe)

## Recent Changes (June 15, 2026)
- Created GitHub repo, pushed all files, enabled Pages
- Marked 4 stories as "Coming Soon" on homepage
- Arjuna's Doubt: 5 cinematic images generated and inserted
- Sun Wakes Up: 6 images generated, page restructured (text/image interleaving), recoloured to pinkish-yellow sunrise theme, image text font enlarged
- Changed story-moment backgrounds to light rose gradient to not overpower images
- Removed duplicate line "The sky was fully golden now" from Scene 3 start
- Cleaned up old image files

## Next Tasks
1. Generate images for remaining 4 stories (River, Roti, Prahlad, Harishchandra)
2. Insert images into those story pages
3. Activate them on homepage (remove "Coming Soon" status)
4. Add audio (TTS) — Google Cloud TTS free tier or OpenAI TTS discussed
