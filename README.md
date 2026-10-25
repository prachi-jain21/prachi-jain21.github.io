# Prachi Jain – Portfolio

A single-page portfolio (plain HTML and CSS, no build step). Works in light and dark mode and on phones.

## Put it on GitHub Pages (free hosting)

1. Sign in to GitHub and click **New repository**.
2. Name it `YOUR-USERNAME.github.io` (replace with your GitHub username) and set it to **Public**. Click **Create repository**.
3. Click **uploading an existing file**, drag in `index.html` and `README.md` from this folder, and click **Commit changes**.
4. Open the repository's **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select branch `main` and folder `/ (root)`, then **Save**.
5. Wait 1–2 minutes. Your site will be live at `https://YOUR-USERNAME.github.io`.

Use that link in the "GitHub or portfolio link" field of applications.

## Add project links later

Once the SQL project and the website are in their own repositories, open `index.html`, find the project tags (for example `<div class="tags">`) and add a line like this inside each project block:

```html
<p><a href="https://github.com/YOUR-USERNAME/REPO-NAME" target="_blank" rel="noopener">View on GitHub</a></p>
```

## Update content

All text lives in `index.html`. Edit it on GitHub with the pencil icon, then commit; the site refreshes in a minute or two.
