# CortX

A mobile-first brain training app in a single HTML file. No build step, no dependencies.

- Interactive 3D brain (canvas) with nine regions, each tied to a test
- Baseline tests: memory, reasoning, critical thinking, visual search, timing, focus, tapping speed, mental rotation, vocabulary
- Scores out of 100 with bands (Strong, Solid, Developing, Early) and an explanation of how each is scored
- Per-region training with tips, progress tracking, and a daily log (sleep, activity, screen time)
- Data stays in your browser (localStorage)

Not an IQ test and not a clinical tool. Scores compare you with your own past results only.

## Run

Open `index.html` in a browser, or host it with any static host (e.g. GitHub Pages). On iPhone, use Share > Add to Home Screen.

## Obsidian

CortX can send each day to an [Obsidian](https://obsidian.md) vault as a Markdown note. Scores and habits go in as note properties. It's free and needs no plugin.

1. In Obsidian, note your vault's exact name (shown in the vault switcher).
2. In CortX, open **Daily**, then **Obsidian › Connection settings**, and enter the vault name.
3. Choose where notes go: a `CortX/YYYY-MM-DD` note per day (sending again updates it), or a CortX section added to your daily note (for example `Daily/{date}`).
4. Tap **Send today to Obsidian** and allow the browser to open Obsidian.

**Export all days (.zip)** gives you one note per day plus a `CortX dashboard.md` with a Dataview table (needs the free Dataview community plugin). Unzip it and drag the folder into your vault.

The send button opens an `obsidian://` link, so Obsidian must be installed on the same device. If you open CortX inside an embedded preview that blocks app links, open `index.html` directly in Safari or Chrome instead.
