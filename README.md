# Portfolio - Carrie Rogers

Personal portfolio and resume site, hosted on GitHub Pages.

## Deploying to GitHub Pages

1. Create a new public repo called `portfolio` at [github.com/new](https://github.com/new)
2. Push this code:

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio site"
git remote add origin https://github.com/cmnordt-collab/portfolio.git
git branch -M main
git push -u origin main
```

3. In the repo settings, go to **Pages** and set the source to **Deploy from a branch** > **main** > **/ (root)**
4. Your site will be live at `https://cmnordt-collab.github.io/portfolio/`

## Updating

Edit `index.html` and push changes. GitHub Pages will redeploy automatically within a few minutes.
