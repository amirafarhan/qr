# Amira Mohamed | QR Landing Page

A lightweight, dependency-free landing page (HTML, CSS, JS) that a QR code on a CV or business card points to.

## Repository structure

```
qr/                  <- a NEW, dedicated repository (suggested name: qr)
├── index.html       <- the whole page (styles + script inline)
├── favicon.svg      <- browser tab icon
└── README.md        <- this file
```

## Updating links

Open `index.html` and edit the `LINKS` array under the "CONFIGURATION" comment. Current values:

- GitHub: https://github.com/amirafarhan
- Portfolio: https://amirafarhan.github.io
- LinkedIn: https://www.linkedin.com/in/amira-mohmed-farhan

## Deploy on GitHub Pages (step by step)

Important: your portfolio already lives in the repository `amirafarhan.github.io`. Do NOT put these files in it. Create a separate repository so nothing existing is touched.

1. Go to https://github.com/new
2. Repository name: `qr` (keep this name permanently, because it is part of your QR URL)
3. Set visibility to **Public** (GitHub Pages on free accounts requires this), leave "Add a README" unchecked, click **Create repository**.
4. On the new empty repo page, click **uploading an existing file**.
5. Drag in `index.html`, `favicon.svg` and `README.md`, then click **Commit changes**.
6. Open **Settings → Pages**.
7. Under **Build and deployment → Source**, choose **Deploy from a branch**.
8. Branch: **main**, folder: **/ (root)**, then click **Save**.
9. Wait 1 to 2 minutes and refresh the Pages settings. It will show "Your site is live at ...".

## Your stable URL

```
https://amirafarhan.github.io/qr/
```

This URL stays the same as long as your username (`amirafarhan`) and the repo name (`qr`) do not change. Editing the page never changes the URL, so you can print the QR code once.

## Verify before printing the QR

1. Open the URL above on your phone using mobile data (not logged in to GitHub).
2. Tap all three buttons and confirm they open the right pages.
3. Only then generate the QR code for that URL (for example with https://www.qr-code-generator.com or any QR tool) and test-scan the final printed version.

Tip: use a QR code with high error correction and print it at least 2 x 2 cm with a white margin.
