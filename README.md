# Our Universe — GitHub Pages Ready

This folder contains a GitHub Pages-ready version of the site.

## Files

- `index.html` — the complete website.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.

## Persistence

The website uses browser `localStorage` for letters, quotes, game data, bucket-list items, timeline entries, date plans, image URLs, and settings. This means data persists across refreshes and browser restarts on the same browser/device, but it is not automatically synchronized across different devices or users.

The date planner still uses `mailto:` to open the visitor's email app.
