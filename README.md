# Three Beaches Dashboard

This project is currently a **single-file accessible web dashboard prototype** for Lagoon Beach, Pilots Bay Beach, and East Beach.

## What it does

- fetches hourly weather + marine conditions,
- scores each beach for **swimming** and **surfing**,
- shows the best windows for today and the next 7 days,
- and lets the user adjust the scoring criteria in the UI.

## Where to get the latest version

Right now there is **no public release URL, app store build, or Git remote configured** for this repository.

That means the latest version currently comes from the repository source itself:

- the current `index.html` file in this repo, or
- a ZIP/export of the current branch from whoever is hosting or sharing the repository.

## Current delivery format

- **Web page:** `index.html`
- **Not yet packaged as:**
  - iPhone app
  - Android app
  - desktop installer
  - downloadable release bundle

## How to run locally

```bash
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173
```

## Adjustable criteria in the UI

The settings panel lets a user change:

- what score counts as a “good” swim,
- what score counts as a “good” surf,
- swim wind / wave / water-temperature / tide settings,
- optional near-high-tide tolerance,
- and surf wave / period / tide settings.

## Suggested next step for public downloads

If you want a real “latest version download” link, the next step is to publish one of these:

1. a GitHub/GitLab release with a ZIP artifact,
2. a hosted static site URL,
3. or a packaged native app build.
