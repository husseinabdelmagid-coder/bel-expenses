# BEL Expenses

Personal monthly budget for Hussein: income, category budgets, day-to-day spending, and the ING savings balance. The starting figures and history come from the BEL Expenses Excel file — income **€7,800**, an October 2026 template budget of **€6,190** across the same 18 categories, and an ING savings balance of **€65,800**. Anything you log after that stays on the phone.

**Pages URL:** https://husseinabdelmagid-coder.github.io/bel-expenses/

## Open it on your phone

1. Open the link above in **Safari** (iPhone) or **Chrome** (Android).
2. Add it to your Home Screen:
   - iPhone: Share → **Add to Home Screen**
   - Android: browser menu → **Install app** or **Add to Home Screen**
3. Open **BEL Expenses** from the icon. It runs full screen and still opens when you are offline.

## Backup tip

Spending you log is saved on the device. After you add entries — and every so often after that — tap the gear at the top right and choose **Backup now**. Keep that file in Files or iCloud. You can restore it from the same menu.

**Save app copy with my data** downloads a single HTML file with your entries inside it. That file is the copy to keep if you change phones.

## In this repo

Static app, no server. `index.html` holds the interface and the Excel history. `manifest.json`, `sw.js`, and `icons/` make it installable and cache the shell for offline use.

GitHub Pages should publish the root of `main` (no build). In the repository: **Settings → Pages → Deploy from a branch → `main` and `/ (root)`**.
