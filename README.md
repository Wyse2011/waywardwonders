# Wayward Wonders

The website for Wayward Wonders, a Final Fantasy XIV roleplay venue on Diabolos, Empyreum Ward 8, Plot 29. It's a magick shop upstairs and an adventurers' guild downstairs.

The site is static: a single `index.html` page plus the images in `img/`. It needs no build step.

## Preview it locally

Open `index.html` in any browser.

## Push to a new GitHub repository

1. Create an empty repository on GitHub, for example `wayward-wonders`. Don't add a README.
2. Open a terminal in this folder (`D:\Dev\wayward-wonders`) and run:

```
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/wayward-wonders.git
git push -u origin main
```

## Publish it free with GitHub Pages

On the repository, go to **Settings → Pages**. Under **Source**, pick **Deploy from a branch**, then choose `main` and `/ (root)` and click **Save**. After a minute or two the site will be live at `https://YOUR-USERNAME.github.io/wayward-wonders/`.

## Editing

- **Contracts:** edit the `contracts` list near the bottom of `index.html`. Each entry has a title (`t`), a type (`k`), a description (`d`), a reward (`r`) and a party size (`n`). The filter buttons are built from the types automatically.
- **Hours, address, Discord link:** search `index.html` for the text you want to change.
- **Images:** replace the files in `img/`, keeping the same names.
