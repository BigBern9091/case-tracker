# The Docket

A small toolkit for a criminal defense practice (Caddo · Cleveland · Oklahoma County). Each tool is a single self-contained HTML file — no build step, no server.

One app, two rooms:

| File | What it is |
|---|---|
| [`index.html`](index.html) | **The Docket** — the app. Case Tracker (docket rail, deadlines with Google Calendar links, grounds & motions, court minute intake, sentencing exposure, OSCN docket links) with **The Story Desk** built in: open it from the rail ("Story Desk") or any case file ("Story"); `#story` links straight to it |
| [`story-desk.html`](story-desk.html) | The Story Desk module — theory-of-the-case narrative builder (acts, beats with sources, voice memos, people, issues). Loaded inside the app; also opens on its own |
| [`case-tracker.html`](case-tracker.html) | Redirect to the app, so old bookmarks keep working |

Data entered in the tools is saved in the browser's `localStorage` on the device you use.

> **Confidentiality:** this repository is public and served on GitHub Pages. Anything committed here — including seeded case data — is readable by anyone.
