# Elan Levin: UX Portfolio

A static, multi-page portfolio site: Home, Projects, About, and Contact.
No build step. Plain HTML/CSS, ready to host directly.

## Deploying to GitHub Pages

1. Copy all files in this folder (`index.html`, `projects.html`, `about.html`,
   `contact.html`, `styles.css`, and the `assets/` folder) into the root of
   your GitHub repo.
2. Commit and push:
   ```bash
   git add .
   git commit -m "Add portfolio site"
   git push
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to `Deploy from a branch`,
   pick your default branch (e.g. `main`) and the `/ (root)` folder, then
   **Save**.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`
   within a minute or two. Re-running steps 2 whenever you edit a file will
   redeploy automatically.

## Before you publish

- **projects.html**: the Little Lemon repo link points to
  `https://github.com/elanlevin1/little-lemon-app`. Update it if the repo
  moves.
- Project photography for the case studies was pulled from your portfolio
  PDF and lives in `assets/`. Swap in higher-resolution shots any time.

## Structure

```
index.html       Home
projects.html    All 6 case studies (Little Lemon, MacDaily, MSCS,
                 Path to Tranquility, Switch Adapted Water Gun, GGTT)
about.html       Bio, working style, skills
contact.html     Contact details
styles.css       Shared design system
assets/          Project images
```
