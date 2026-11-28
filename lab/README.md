# Lab diary

One unlisted page at `/lab/` holds dated entries, newest first. The public site navigation does not link here. The page requests `noindex`; it is accessible without authentication.

Each entry pairs a frozen interactive snapshot on the left with a walkthrough on the right. Both expand independently; narrow screens stack them. The hosted preview omits the optional lab-note query parameter, since the diary supplies its context. Use the date as each chapter’s heading, without a separate title. Add future entries at the top of `index.html`, with stable date-based anchors; the page also sorts entries by their machine-readable dates, newest first. Keep earlier snapshot assets unchanged so the diary records what was explored at that time.

## 28 November 2026 — Researcher view

The static comparison under `assets/researcher-view-2026-11-28/` opens Current by default and offers Sketch as a second tab. Current preserves application revision `4980e70a7c1f33d4e4c5173b1df80709d0c6e4b4`, with only a researcher deep link and relative asset paths added. Sketch uses the dataset's UMAP topic positions and an optional chronological line through each year's most-cited paper. Neither the current application nor the earlier diary snapshot is replaced.

Built with `npm run build -- --base ./`; the application, comparison baseline and data are served together. Hosted HTML requests no indexing. The 4:44 MP4 is a 1600-pixel-wide H.264/AAC viewing copy with fast-start metadata. The original recording is retained separately.

## 22 November 2026 — Researcher view

The static application under `assets/researcher-view-2026-11-22/` contains the Current, Simplified and Embedding-based sketches. Embedding positions are simulated from titles. The application and its data are served together; no build or API service is needed for playback. Local fonts retain their licence notices.

The application was built from the unchanged 22 November snapshot source, with Vite’s base URL set to `/lab/assets/researcher-view-2026-11-22/`. The HTML title and indexing metadata were adjusted for this hosted copy. The MP4 walkthrough is a compressed viewing copy.
