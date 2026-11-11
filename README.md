# Card Picker

Single-file web app (`index.html`) that tells you which of your credit cards to use for a given spend:
HDFC Millennia, Axis Atlas, HDFC Tata Neu Infinity and Scapia.

Open `index.html` in any browser (no build/install). Tabs: Which card? · Cheat sheet · Card benefits · How to maximise · My month (cap tracking, stored in your browser).

Reward rules live in the `CARDS` / `evaluate()` section of the script — bank terms change often, so verify and edit as needed.

## Install on your phone (PWA)

Once deployed to GitHub Pages (Settings → Pages → Source: GitHub Actions; the workflow runs on pushes to `main`), open the site on your phone:
- iPhone (Safari): Share → Add to Home Screen
- Android (Chrome): ⋮ → Install app

It works offline after the first load. Logged spends are stored on the device only.
