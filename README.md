# AI Education Game

**Practical AI literacy through interactive demos.**

Built as a single-file, Cursor-friendly HTML + Tailwind app. Works great on Android phones in landscape mode. GitHub Pages ready.

## Run locally
Just open `index.html` in any browser (or use Cursor's Live Server).

## Deploy
One-command GitHub Pages:
```bash
git add . && git commit -m "Update AI Education Game" && git push
```
Then enable GitHub Pages in repo settings.

## What's inside
- 4 interactive modules, each with a **3-step lesson** (learn → practice → challenge/debrief)
- Prompt Lab rubric scoring (task, length, constraints, tone)
- Decision Simulator with live feature weights and loan debrief
- Bias Lab with 5 scenarios + training-data fix challenge
- Hallucination Lab — spot false confident answers and verification habits
- Learning path with **Continue**, level unlocks, and 100% certificate (12 steps)
- Classroom mode toggle (unlock all levels)
- **PWA**: `manifest.json`, `sw.js`, install banner, offline app shell
- Local progress tracking (resumes at your last completed step)
- Mobile-first responsive design
- Zero app dependencies beyond CDNs (when online)

## Install as an app
1. Serve over HTTPS (GitHub Pages works).
2. Open in Chrome or Edge — use the **Install** banner or browser menu → Install app.
3. On iOS Safari: Share → **Add to Home Screen**.

Offline note: the service worker caches the app shell (`index.html`, manifest, icon). CDN assets (Tailwind, fonts) need network unless you self-host them.

Made for real learning, not student projects.