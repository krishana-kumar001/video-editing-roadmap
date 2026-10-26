# Video Editing Roadmap

A single-page website that lays out a seven-step path for becoming a professional video editor: what to learn, which tools to pick, how to grow through three skill levels, and how to find clients.

## What's on the page

- **Cover** with a large serif title, a short deck and a figure of a four-track editing timeline.
- **Contents list** that links to every chapter.
- **A - Learn**: 10 YouTube channels in a ruled index, grouped by software basics, intermediate to advanced editing, and effects and templates.
- **B - Specialise**: 13 more channels grouped by color and filmmaking, sound and motion, and animation and 3D. Every row links to the channel.
- **Step 01 - Master design first**: Photoshop and Illustrator fundamentals, with three small figures.
- **Step 02 - Choose your arsenal**: Premiere Pro + After Effects, or the free DaVinci Resolve + Fusion setup.
- **Step 03 - Three levels of mastery**: beginner, intermediate and advanced.
- **Steps 04-05**: find your editing style and build a portfolio of 5-7 best projects.
- **Steps 06-07**: client acquisition (high-volume platforms vs personal brand) and using AI tools to work faster.

## Design

- Editorial magazine layout: Bodoni Moda headlines, Newsreader body text and IBM Plex Mono labels.
- Off-white paper with black ink and a single orange accent. A matching black dark theme. Both follow the visitor's system setting.
- Ruled chapter headers, figures with captions and a ruled channel index instead of cards.
- Responsive from phones to wide desktops.
- Motion is kept quiet: the title lifts in line by line, a rule draws across the cover, the timeline playhead sweeps, sections fade in on scroll and rows shift on hover. All motion is switched off for visitors who prefer reduced motion.
- Fonts load from Google Fonts, with Georgia and system fallbacks.

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
