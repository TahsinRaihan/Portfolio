# Tahsin Raihan Robbani — Portfolio

A single-file, dependency-free futuristic portfolio. No build step, no npm install — just open it.

## Run it
1. Keep all three files in the same folder: `index.html`, `profile.jpg`, `Tahsin_Raihan_Robbani_CV.pdf`.
2. Double-click `index.html` to open it in any browser — or for the smoothest experience, serve it locally:
   ```
   cd portfolio
   python3 -m http.server 8000
   ```
   then visit `http://localhost:8000`.
3. To deploy for free: drag the folder into [Netlify Drop](https://app.netlify.com/drop), or push it to a GitHub repo and enable GitHub Pages.

## What's inside
- **⌘K command palette** — press Ctrl/Cmd+K to jump to any section, project, or link.
- **Student Tutor spotlight** — dedicated HUD card for your CSE230 appointment.
- **Research deep-dive modal** — click "Open Technical Deep-Dive" under the Research section.
- **Project bento grid** — click any project card for the full write-up.
- **Mobile dock** — bottom floating nav appears automatically on small screens.
- **CV download button** — pulls directly from the bundled PDF.

## Customize
- Colors/fonts are all CSS variables at the top of `index.html` (`:root`) — easy to retune.
- Project and research content lives in the `projects` array near the bottom of the `<script>` — edit text there.
- Swap `profile.jpg` for a new headshot any time (keep the filename, or update the `<img src>` in the Hero section).
