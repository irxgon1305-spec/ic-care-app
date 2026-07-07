# IC Care 💛

A warm, cozy single-page web app — a little pocket guide for eating gently with
**interstitial cystitis (IC)**. Made as a supportive, non-clinical reference:
what IC is, why flares happen, food guidance, easy recipes, gentle daily habits,
and a low-stakes "Safe or Avoid?" flashcard game.

## ✨ What's inside

- **Hub screen** with a warm greeting and tap-to-navigate category tiles
- **Learn** sections: What is IC?, Why Flares Happen, Around Your Period,
  What's Happening in Your Body
- **Food** sections: Safe Foods, Foods to Avoid (grouped, scannable chips)
- **Easy Recipes** — simple, IC-friendly meals
- **Gentle Daily Habits** — small everyday comforts
- **Safe or Avoid?** — a flip-card game, just for fun

## 🛠️ Tech

- A single, self-contained `index.html` — HTML, CSS, and JavaScript inline.
- **No build step, no backend, no database, no browser storage.** All state
  lives in memory.
- Mobile-first, keyboard accessible, and respects reduced-motion preferences.

## 🚀 Running locally

Just open `index.html` in any browser. That's it.

Optionally, to serve it over `http://localhost` (Windows, no extra installs):

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File serve.ps1 -Port 4599
```

Then visit http://localhost:4599/. (`serve.ps1` is a small dev-only helper and
is not needed for deployment.)

## 🌐 Deployment

Static site — deploys as-is with **no build command** and the **publish
directory set to the repo root**. Hosted on Netlify with auto-deploy on push.

## 🩺 A gentle note

This app is for information and comfort only — it is **not medical advice,
diagnosis, or treatment**. Everyone's IC is different; please check with a
doctor or dietitian before making changes.

---

Made with love. 💛
