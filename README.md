# BabyTracker Live 🍼

A tiny, read-only live status page for BabyTracker.

It gives family a simple browser link to check the baby's latest care status without installing the app.

## What It Shows ✨

- 🍼 Time since the last milk feed
- 📊 Last milk amount and today's total
- 🧸 Latest diaper update
- 🌙 Current sleep status
- 💛 Gentle care reminders
- 🌎 English and Chinese
- 🔄 Manual refresh and automatic 60-second refresh

## How It Works ☁️

The BabyTracker app publishes a small read-only snapshot to iCloud. This page reads that snapshot with a private link token and displays it in a soft, pixel-style UI that matches the app.

Example link:

```text
https://sinexu.github.io/babytracker-live-page/?token=PRIVATE_TOKEN
```

Anyone with the link can view the live page, so treat the link like a private family link.

## Local Preview 🖼️

Open `index.html` directly in a browser.

Without a configured iCloud web token, the page shows sample data for previewing the design.

## Deploy 🚀

This is a static GitHub Pages site.

```bash
git add index.html README.md assets
git commit -m "Update BabyTracker live page"
git push
```

GitHub Pages URL:

```text
https://sinexu.github.io/babytracker-live-page/
```
