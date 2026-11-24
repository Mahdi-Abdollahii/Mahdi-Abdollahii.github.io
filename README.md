# Mahdi Abdollahi — Academic Website

A responsive, minimalist academic website built with plain HTML, CSS, and JavaScript. It is designed to be hosted free on GitHub Pages.

## Files

- `index.html` — website content
- `styles.css` — layout, typography, colors, responsive styling
- `script.js` — mobile navigation and current year
- `assets/` — place your CV PDF and optional profile photo here

## Before publishing: personalize these items

1. In `index.html`, replace `YOUR_EMAIL@example.com` with your public academic email.
2. Replace the ORCID, Google Scholar, ADS, and GitHub profile links with your own profile URLs.
3. Check the publication details, year, author list, journal status, DOI, ADS, and arXiv links. The site currently includes two entries based on the information available; verify them before publishing.
4. Add your CV PDF as `assets/Mahdi_Abdollahi_CV.pdf`.
5. The profile portrait is included as `assets/mahdi.png`. To replace it, upload another image using the same filename and path.
6. Review the biography and project descriptions and edit anything that does not match your preferred public profile.

## Publish with GitHub Pages

1. Create or sign in to your GitHub account at https://github.com/.
2. Create a **new repository** named exactly `YOUR-USERNAME.github.io` (replace `YOUR-USERNAME` with your GitHub username).
3. Set the repository visibility to **Public**.
4. Upload the contents of this folder to the repository root. `index.html` must be at the top level, not inside another folder.
5. Open the repository's **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch `main` and folder `/ (root)`, then click **Save**.
8. Wait a few minutes. Your site should appear at `https://YOUR-USERNAME.github.io/`.

If your GitHub Pages settings offer GitHub Actions instead, the plain static site can also be deployed using a Pages workflow, but branch deployment is the simplest route for these files.

## Updating the site

Edit `index.html`, `styles.css`, or `script.js` in GitHub and commit the changes. GitHub Pages will publish updates automatically.

## Notes

- Hosting and the default `github.io` address are free.
- Google Fonts are loaded from Google Fonts; if unavailable, the site falls back to system fonts.
- This site does not collect visitor data and does not use analytics.
- The CV download link will only work after you add your PDF at the path above.
