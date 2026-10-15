# The Red Book of Arman (Portfolio)

## Deploy on GitHub Pages
1. Create a repo (for example `arman-portfolio`) and upload all these files, keeping the folders.
2. Settings > Pages > Source: Deploy from a branch > `main` / root.
3. Your site appears at `https://<username>.github.io/<repo>/`.
4. Tip: for the 404 page CSS to load on a project site, change `/css/style.css` and `/` in `404.html` to `css/style.css` and `./`. If you name the repo `<username>.github.io`, leave it as is.

## Make the dead links real
- In `index.html`, remove `class="dead"` from a link and put your real URL in `href`.
- Email: use `href="mailto:you@example.com"`.
- Edit jokes in `js/main.js`.
