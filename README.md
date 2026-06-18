# Skyquire — Planning Workspace

A single-page planning workspace for Skyquire's road to launch on **Dec 19, 2026**.
Open `index.html` to use it — a sidebar switches between every board in place.

## What's inside

- **index.html** — the single-page workspace (sidebar + embedded boards)
- **launch/** — the launch plan
  - `launch-whiteboard.html` — 6-phase roadmap
  - `launch-timeline.html` — month-by-month Gantt
  - `launch-schema.html` — target system & data schema
  - `launch-jira.html` — epics & stories roadmap
  - `launch-checklist.html` — registration → launch checklist (interactive)
- **seller-platform.html** — the separate seller product plan
- **whiteboard.html / schema.html / jira-board.html** — the 3-day sprint boards
- **hub.html** — the older multi-page hub (kept for reference)

## Deploy (Vercel)

Pure static site — no build step. On Vercel, set **Framework Preset: Other**,
leave the build command empty, and the output directory as the repo root.
Every push to `main` redeploys.
