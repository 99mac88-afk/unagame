# UNA game

A school-themed endless jumper for phones (and desktop). Bounce up the desks, collect gold «пятёрки», stomp the «двойки», and unlock all 15 characters.

Everything is in a single `index.html` — no build step, no server code.

## What's in the game

- **Gameplay:** your character bounces automatically; you steer left and right. The climb goes from the classroom through the sky, a sunset and night into space.
- **Desks:** ordinary, blue (moves sideways), old (breaks after one bounce), and a stack of textbooks (super jump).
- **Pickups:** gold star «5» (+10 points), paper airplane (flies you up and protects you).
- **Enemies:** the red «2» ends the round if you touch it from the side or below; land on it from above for +25.
- **15 characters** with the original names and unlock costs (0 to 100 000 total points).
- **Daily wheel** (every 12 hours), **ELO ranks** (Без звания → Градиент) with 7-day seasons, profile stats.
- **Your own photos:** Profile → «Свои фото персонажей» lets you replace any portrait (or the menu background) with a photo. Photos are resized and stored only on that device.
- Sound effects (synthesised, no audio files), vibration, touch / tilt / keyboard controls.

Progress is saved in the browser under the key `una_save_v1`, the same key the previous version used, so existing progress carries over.

## Controls

| Device | Move | Pause |
| --- | --- | --- |
| Phone | Hold the left or right half of the screen (or switch to tilt in Profile) | ❚❚ button |
| Computer | ← → or A / D | Esc or P |

## Publish it as a website

### Option 1 — GitHub Pages (free, uses this repository)

1. GitHub Pages on a free account needs a **public** repository. If this repo is private, go to **Settings → General → Danger Zone → Change visibility → Public** (or use a paid plan, which allows Pages on private repos).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick **main** and **/ (root)**, then **Save**.
4. After a minute the game is live at `https://<your-username>.github.io/unagame/`.

Every push to `main` updates the site automatically.

### Option 2 — Netlify Drop (no account settings needed)

Open <https://app.netlify.com/drop> and drag this whole folder onto the page. You get a public link right away.

### Install on a phone

Open the site, then **Share → Add to Home Screen** (iPhone) or **⋮ → Install app** (Android). It opens full-screen like an app and keeps working offline.
