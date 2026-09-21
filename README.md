# Learning Tracker

A modern browser-based learning management website for organizing everything you are learning.

## Features

- Create unlimited nested learning levels
- Add main learning items and child items
- Add subchildren at any depth
- Track not started, in progress, and completed statuses
- Automatically calculate progress from completed leaf items
- Select and save icons for learning items
- Persist data with localStorage
- Responsive desktop and mobile layout
- GitHub Pages deployment with GitHub Actions

## Tech Stack

- React
- TypeScript
- Vite
- CSS
- localStorage

## Run Locally

```bash
npm install
npm run dev
```

## Publish

This repository is configured to deploy automatically to GitHub Pages from the `main` branch.

1. In the GitHub repository, open **Settings > Pages** and set **Source** to **GitHub Actions**.
2. Push the project to `main`:

```bash
git add .
git commit -m "Prepare site for publishing"
git push origin main
```

3. Wait for the **Deploy Learning Tracker** workflow to finish in the **Actions** tab.
4. Open `https://sanjeeva-2006.github.io/learning-tracker/` to verify the site.
5. In [Google Search Console](https://search.google.com/search-console), add the URL-prefix property, use **URL inspection**, and request indexing for the published URL.
