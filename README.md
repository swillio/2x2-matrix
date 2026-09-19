# 2x2 Matrix (Eisenhower Matrix Builder)

A simple website for turning a messy to-do list into a clear priority matrix.

Use it to sort work into four quadrants, focus on what matters most, and quickly export a clean matrix for sharing or planning.

## Why use it

- Prioritize tasks by urgency vs. importance
- Rename axes and quadrants for any framework (not just Eisenhower)
- Add notes directly inside each quadrant
- Print or save as PDF for meetings and planning docs
- Keep your matrix private in your own browser

## What you can do on the page

1. Set a matrix title.
2. Name both axes (left/right and top/bottom).
3. Optionally define acceptance criteria for each axis side.
4. Rename the four quadrant labels.
5. Add notes inside each quadrant.
6. Toggle presentation mode for a cleaner full-screen view.
7. Print or save to PDF.

## Privacy

Your matrix is saved in your browser using `localStorage` so your work stays available when you reopen the page on the same device/browser.

There is no backend in this project and no data is sent by the app.

## Open the website

Open `index.html` in your browser from this project folder.

If you prefer serving files over HTTP:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.
