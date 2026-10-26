# Video Editing Roadmap

A single-page website that lays out a seven-step path for becoming a professional video editor: what to learn, which tools to pick, how to grow through three skill levels, and how to find clients.

## What's on the page

- **Top bar** with a pulsing REC dot and a scroll progress line.
- **Hero** with a large film-title headline, an animated editing-timeline illustration.
- **Learning resources**: 23 YouTube channels shown as simple link lists, grouped by software basics, intermediate to advanced editing, effects and templates, color and filmmaking, sound and motion, and animation and 3D. Each name links to the channel.
- **Step 1 - Master design first**: Photoshop and Illustrator fundamentals.
- **Step 2 - Choose your arsenal**: Premiere Pro + After Effects, or the free DaVinci Resolve + Fusion setup.
- **Step 3 - Three levels of mastery**: beginner, intermediate and advanced.
- **Steps 4-5**: find your editing style and build a portfolio of 5-7 best projects.
- **Steps 6-7**: client acquisition (high-volume platforms vs personal brand) and using AI tools to work faster.

## Design and features

- Pure HTML and CSS in one file with a small inline script. No build step, no dependencies.
- Record-red accent on a clean light background, with a matching deep-ink dark theme. Both follow the visitor's system setting.
- Clean sentence-case headings in a single-column layout.
- Responsive layout that works from phones to wide desktops.
- Motion: staggered page-load entrance, a moving timeline playhead, soft scroll reveals and hover effects. All motion is switched off for visitors who prefer reduced motion.
- Fonts (Archivo, Hanken Grotesk, IBM Plex Mono) load from Google Fonts, with system fallbacks.

## Project structure

```
.
├── index.html   # the whole site
└── README.md
```

## Run locally

Open `index.html` in any browser. To serve it instead:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-username>.github.io/<repo-name>/`.

## Credits

The roadmap content is based on the Video Editing Roadmap by [Somrat Dutta](https://www.youtube.com/@somratdutta) and [Aasil Khan](https://www.youtube.com/@aasil_khan_). All credit for the original roadmap goes to them. This repository is a recreated page with its own layout, illustrations and animation.
