# WorkoutHome

A 12-week return-to-training plan (3 strength sessions + 1 conditioning session per week) with a guided
session player: timed warm-up, set-by-set logging, rest timers, interval timers, cool-down, and progress tracking.

Equipment assumed: adjustable dumbbells (2–12 kg), one 8 kg kettlebell, a sturdy chair.

## Use it

Open `index.html` in any browser, or host the repo with GitHub Pages (Settings → Pages → deploy from branch, root).
On a phone, use "Add to Home Screen" for a full-screen app. Progress is stored in the browser (`localStorage`);
use **Progress → Copy backup** to move it between devices.

## Edit it

Everything lives in `src/app.html` (plan data at the top of the script: `EX`, `TPL`, `SCHEME`, `HIIT`).
Run `./build.sh` to regenerate `index.html`.
