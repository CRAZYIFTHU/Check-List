# RESET — Daily Tracker

A lightweight, mobile-first Progressive Web App for tracking three daily habits:
- Sleep on time
- Eat meals on time
- Avoid excessive phone use

## Features
- Three daily habit checkboxes with automatic saving
- Daily completion percentage
- Calendar history with complete, partial, and missed days
- Edit previous days
- Current and best full-completion streaks
- Offline app shell after the first successful visit
- No account, server, analytics, or paid service
- Data stays in this browser on this device

## Start date
The tracker begins on **28 November 2026**. Dates before that and future dates cannot be edited.

## Run locally
Serve this folder from a local HTTP server (service workers require HTTPS or localhost). Opening index.html as a file will show the tracker but will not enable offline installation.

## Publish with GitHub Pages
1. The repository must be **public** on GitHub Free for GitHub Pages. Alternatively, use a plan that supports Pages for private repositories.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. The workflow in `.github/workflows/pages.yml` deploys the site on pushes to `main`.
5. After the workflow succeeds, the site URL will appear in the workflow deployment and Pages settings.

## Install on Android
Open the published HTTPS site in Chrome, tap the three-dot menu, choose **Install app** (or **Add to Home screen → Install**), then launch RESET from your home screen.

## Data note
Progress is saved with localStorage. It is not synced between devices. Clearing this site's browser data can erase your tracker history.