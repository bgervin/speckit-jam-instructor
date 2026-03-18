# SpecKit Hands-on Lab — Instructor Materials

Everything you need to run the **AI Forward SpecKit Hands-on Lab** using The $100 Test app.

## 📦 Three Repos

| Repo | Purpose | Link |
|---|---|---|
| **speckit-jam-instructor** (this repo) | Instructor materials, HOL page, scripts | You're here |
| **speckit-jam-starter** | Pre-built app that participants fork | [→ Starter Repo](https://github.com/gim-home/speckit-jam-starter) |
| **speckit-jam-participant** | Completed workshop (fork of starter) | [→ Participant Repo](../speckit-jam-participant) |

## 🌐 Hands-on Lab Page

The HOL instruction page is in `docs/index.html`. To serve it:

### Option 1: GitHub Pages
1. Go to repo Settings → Pages
2. Set source to "Deploy from a branch"
3. Select `main` branch, `/docs` folder
4. The page will be live at `https://YOUR_ORG.github.io/speckit-jam-instructor/`

### Option 2: Open locally
Just open `docs/index.html` in a browser — it's fully self-contained with no external dependencies.

## 📋 Session Checklist

### Before the Session
- [ ] Starter repo is published and accessible
- [ ] HOL page is deployed and tested
- [ ] Pre-read email sent to attendees (see `docs/pre-read.md`)
- [ ] Dry run completed
- [ ] VS Code + Copilot CLI working on presenter machine

### During the Session
- [ ] Share HOL page link in chat
- [ ] Brief intro (5 min) — show existing app, point out the gap
- [ ] Lab 1 guided walkthrough (15-20 min)
- [ ] Stretch labs for fast movers (remaining time)
- [ ] Wrap-up: Why SpecKit? (5 min)

### Session Timing (~45 min)
| Phase | Duration |
|---|---|
| Intro & Getting Started | 5 min |
| Lab 1: View Results Dashboard | 20 min |
| Labs 2-4: Stretch Goals | 15 min |
| Wrap-up & Q&A | 5 min |

## 📁 Repo Structure

```
├── docs/
│   ├── index.html       # HOL instruction page (GitHub Pages)
│   └── pre-read.md      # Pre-read template for attendees
├── scripts/
│   └── instructor-notes.md  # Presenter talking points
└── README.md            # This file
```
