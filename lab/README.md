# Lab diary

One unlisted page at `/lab/` holds dated entries, newest first. The public site navigation does not link here. The page requests `noindex`; it is accessible without authentication.

Each entry pairs a frozen interactive snapshot on the left with a walkthrough on the right. Both expand independently; narrow screens stack them. The hosted preview omits the optional lab-note query parameter, since the diary supplies its context. Add future entries to `index.html`, with stable date-based anchors. Keep earlier snapshot assets unchanged so the diary records what was explored at that time.

## 22 November 2026 — Researcher view

The static application under `assets/researcher-view-2026-11-22/` contains the Current, Simplified and Embedding-based sketches. Embedding positions are simulated from titles. The application and its data are served together; no build or API service is needed for playback. Local fonts retain their licence notices.

The application was built from the unchanged 22 November snapshot source, with Vite’s base URL set to `/lab/assets/researcher-view-2026-11-22/`. The HTML title and indexing metadata were adjusted for this hosted copy. The MP4 walkthrough is a compressed viewing copy.
