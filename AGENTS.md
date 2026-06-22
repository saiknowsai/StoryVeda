# StoryVeda — AI Assistant Context

## Project Identity
**StoryVeda** — Children's Vedic storytelling website. Ancient wisdom through beautiful stories for ages 3-10.

## Working Directory
`C:\Users\sweth\Documents\StoryVedaLocal`

## Live Site
`https://saiknowsai.github.io/StoryVeda/`

## Git
- Path: `C:\Users\sweth\AppData\Local\GitHubDesktop\app-3.5.12\resources\app\git\cmd\git.exe`
- User: saiknowsai
- Repo: https://github.com/saiknowsai/StoryVeda (public)

## File Structure
```
StoryVedaLocal/
├── index.html                    ← Homepage (age-filter layout, 6 story cards, 2 active + 4 coming soon)
├── stories by age/
│   ├── 3-5/
│   │   ├── the-sun-wakes-up.html     ✅ Live · Mantra (pinkish-yellow sunrise theme, 6 images)
│   │   ├── the-sun-wakes-up/         (6 scene images)
│   │   ├── why-the-river-sings.html  ⏳ Coming Soon
│   │   └── why-the-river-sings/      (image-prompts.txt only)
│   ├── 6-8/
│   │   ├── the-boy-who-shared-his-last-roti.html  ⏳ Coming Soon
│   │   ├── the-boy-who-shared-his-last-roti/      (image-prompts.txt only)
│   │   ├── prahlad-and-the-pillar-of-fire.html    ⏳ Coming Soon
│   │   └── prahlad-and-the-pillar-of-fire/        (image-prompts.txt only)
│   └── 9-10/
│       ├── arjunas-doubt.html       ✅ Live · Mahabharata (cinematic theme, 5 images)
│       ├── arjunas-doubt/           (5 scene images + image-prompts.txt)
│       ├── king-harishchandras-promise.html  ⏳ Coming Soon
│       └── king-harishchandras-promise/      (image-prompts.txt only)
├── archive/                       ← Old versions preserved
├── .gitignore
├── NOTES.md
└── AGENTS.md
```

## Key Conventions
- Each story in its own age folder under `stories by age/`
- Each story has a matching image folder (e.g., `arjunas-doubt/` for `arjunas-doubt.html`)
- Story pages follow template: hero → scenes (text + image interleaved) → mantra/quote → value box → reflection → interactive quiz → nav
- Homepage sections: `#home`, `#why`, `#stories`, `#about`, `#connect`
- Story nav back-links: `../../index.html#stories`
- Subscribe link: `index.html#connect`
- Only Sun Wakes Up and Arjuna's Doubt are clickable; others marked "Coming Soon"

## Live Stories (2/6)
1. **The Sun Wakes Up** — Mantra · ages 3-6 · Gayatri Mantra · gratitude · pinkish-yellow sunrise theme · 6 cinematic images
2. **Arjuna's Doubt** — Mahabharata · ages 7-10 · courage · deep purple/gold theme · 5 cinematic images

## Coming Soon (4/6)
3. **Why the River Sings** — Nature · ages 4-7 · Ganga · creation
4. **The Boy Who Shared His Last Roti** — Values · ages 5-8 · generosity
5. **Prahlad and the Pillar of Fire** — Puranas · ages 6-10 · faith
6. **King Harishchandra's Promise** — Dharma · ages 8-10 · truth

## Image Naming Convention
- `scene{N}-{description}.jpg` — one per scene, stored in story's image folder
- Arjuna uses spaces in filenames: `scene1-armies final.jpg` etc.
- Sun uses hyphens: `scene1-tiptoe.jpg` etc.

## Notes
- Root-level `arjunas-doubt.html`, `sun-wakes-up.html`, `Arjunas-Doubt/`, `Sun-Wakes-Up/` are legacy — kept in git for reference
- Original full index.html is in `archive/`
- User is in India, prefers free/low-cost tools
- Static HTML project (no build tools, no frameworks)
- Story pages use embedded CSS, no external stylesheets
- Images generated via Google Flow; prompts in image-prompts.txt files
