# 2x2 Matrix

A minimal, single-page 2x2 matrix builder. No framework, build step, server, or dependencies.

## Run locally

Open `index.html` directly in a browser.

For a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Push to GitHub

Create an empty GitHub repository, then from this folder run:

```bash
git init
git add .
git commit -m "Initial 2x2 matrix"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Host with GitHub Pages

In the GitHub repository:

1. Open **Settings -> Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**.
4. Save.

The site URL will typically be:

`https://YOUR_USERNAME.github.io/YOUR_REPO/`

The empty `.nojekyll` file tells GitHub Pages to serve this as a plain static site without Jekyll processing.

## Files

- `index.html`: the entire app
- `.nojekyll`: disables Jekyll processing

## Privacy

The app stores matrix content in the browser's `localStorage`. There is no backend and the page itself does not transmit that content anywhere.
