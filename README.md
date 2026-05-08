# DJ Riddim Ridder — Official Website

## Folder Structure

```
dj-riddim-ridder/
├── index.html              ← HOMEPAGE
├── .nojekyll               ← REQUIRED for GitHub Pages (already included)
├── css/
│   └── style.css
├── js/
│   └── main.js
├── pages/
│   ├── events.html
│   ├── music.html
│   ├── book.html
│   └── contact.html
├── video/
│   └── Video_Project_3.mp4 ← ADD YOUR VIDEO HERE
└── README.md
```

## GitHub Pages Setup (IMPORTANT — follow exactly)

1. Create a repo named **dj-riddim-ridder** (or any name)
2. Upload ALL files **maintaining the exact folder structure above**
3. Add your `Video_Project_3.mp4` inside the `video/` folder
4. Go to **Settings → Pages → Source → Deploy from branch → main → / (root) → Save**
5. Wait ~60 seconds, then visit: `https://YOUR-USERNAME.github.io/dj-riddim-ridder`

## Why `.nojekyll` is required

GitHub Pages uses Jekyll by default, which can interfere with serving
static files. The `.nojekyll` file tells GitHub to skip Jekyll processing.

## Video File

Drop `Video_Project_3.mp4` into the `video/` folder.
The hero section auto-plays it looped and muted. If missing, a logo fallback shows.
