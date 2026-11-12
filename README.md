# SchoolSafe

A lightweight, responsive directory of game and web shortcuts. Built as a static site with plain HTML, CSS, and JavaScript — no build step or dependencies required.

## Preview locally

Open `index.html` in a browser.

## Publish with GitHub Pages

1. Create a new repository on GitHub (for example, `schoolsafe`).
2. Upload `index.html` to the repository's **root**. You can also upload this `README.md`.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)` folder, then click **Save**.
6. Wait for GitHub Pages to publish. Your site address will appear in the Pages section, usually `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Customize

The website links are stored in the `links` array near the bottom of `index.html`. Each entry has:
- `name`: the label shown on the card
- `host`: the domain shown below the label
- `url`: the destination

Add or remove entries in that array to update the directory.

## Important note

The links were imported from the supplied list and have not been individually reviewed for safety, privacy, availability, or school-policy compliance. The SchoolSafe name is the site's title, not a guarantee that every destination is safe or approved. Review links before sharing this directory, especially in a school environment.
