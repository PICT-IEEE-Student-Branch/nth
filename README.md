# NTH — Network Treasure Hunt

**NTH** is PISB's famous **24-hour online puzzle hunt**. You have the whole internet at your fingertips and can use any tool or approach you like. Each answer leads to the next, and the team that gets furthest wins. It runs during **Credenz** and is also promoted at **Credenz Tech Dayz (CTD)**.

🌐 Live: [nth.credenz.co.in](https://nth.credenz.co.in)

## Editions

| Year | Website / platform | Questions & answers |
|---|---|---|
| **2026** | 🔜 *Coming soon* | 🔜 *Coming soon* |

## 📤 Where do I push?

| What you have | Put it in |
|---|---|
| **NTH website / platform code** (frontend, backend, admin panel) | `<year>/website/`, e.g. [`2026/website/`](2026/website/) |
| **Questions, hints, answers** | `<year>/questions/`, **only after that year's hunt has closed** |
| Notes for next year's team (what broke, how you hosted it, costs) | `<year>/README.md` |

```
nth/
└── 2026/
    ├── README.md        ← what this edition was, how to run/deploy it, who built it
    ├── website/         ← NTH website code goes here
    └── questions/       ← questions + answers (after the hunt closes)
```

**Deploying from this repo:** on Vercel or Netlify, set the project's *Root Directory* to `2026/website`.

New to Git? Follow [**How to push to PISB GitHub**](https://github.com/PICT-IEEE-Student-Branch/.github/blob/main/CONTRIBUTING.md). It covers both drag-and-drop upload and command-line Git.

## ⚠️ Before you push the website

- **No secrets.** Never commit `.env`, database URLs, API keys or admin passwords. Commit a `.env.example` with empty values instead. A [`.gitignore`](.gitignore) that skips `.env`, `node_modules/` and build folders is already in this repo.
- **No player data.** Don't commit registration exports, leaderboards with names, emails or phone numbers.
- **No answers while the hunt is live.** This repo is public.

---

Part of the [PICT IEEE Student Branch](https://github.com/PICT-IEEE-Student-Branch) · See all [Credenz events](https://github.com/PICT-IEEE-Student-Branch/credenz)
