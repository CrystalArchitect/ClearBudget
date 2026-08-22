# ClearBudget

**Privacy-first personal budget app.** 100% local-first. Your data never leaves your device. No accounts, no servers, no tracking.

## Live / Use

- **Open the file**: Download `index.html` and open it in any modern browser. Works completely offline.
- **GitHub Pages** (after enabling): https://xfreeze2.github.io/ClearBudget/

To enable Pages: Repo Settings → Pages → Source: Deploy from a branch → `main` / root → Save.

## Features

- Add income and expenses
- Categories, dates, notes, and recurring items (with one-click apply for the current month)
- Monthly budget targets (overall + per category)
- Visual spending breakdowns (progress bars + pie)
- Search and filters (type, category, text)
- Import / export through CSV (handles quotes, commas, refunds)
- Local-first storage with clear privacy messaging
- Responsive mobile-first interface
- Proper empty, error, and success states
- Keyboard accessible

## Privacy Guarantee

ClearBudget stores **everything only in your browser’s local storage** on your device.  
Nothing is ever sent to any server. There is no account, no cloud, no analytics, no tracking.  
Export a CSV backup anytime. Clearing browser data or using the in-app Reset button permanently deletes everything. We cannot recover it because we never had it.

## Sample Data

Use the “Load Sample Data” button to explore with realistic edge cases:
- Refunds (negative expense)
- Zero-value transactions
- Large amounts ($125,000+)
- Month boundaries
- Notes containing commas and quotes
- Recurring templates

## Tech

- Single self-contained HTML file (vanilla JS + CSS)
- Integer cents for money math (no float surprises)
- No frameworks, no build step, no external dependencies
- Works offline forever after first load

## License

MIT — free to use, modify, and share.

Built with maximum execution energy.
