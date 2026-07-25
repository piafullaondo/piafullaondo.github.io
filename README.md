# Pia Fullaondo — Data Science Portfolio

A personal portfolio site showcasing data science projects, articles, and certificates.

🔗 **Live site:** `https://piafullaondo.github.io/<repo-name>/`

## About

This site is a single-page portfolio with a hero carousel, an about section, a project grid,
a list of articles, and courses/certificates — plus standalone pages for each project.

## Tech stack

- HTML5 & CSS3
- [Bootstrap 5](https://getbootstrap.com/) for layout, navbar, and carousel
- Vanilla JavaScript for the active-nav-link-on-scroll behaviour

## Running locally

No build step needed — it's static HTML/CSS/JS.

```bash
git clone https://github.com/piafullaondo/<repo-name>.git
cd <repo-name>
# then just open index.html in a browser, or serve it:
python3 -m http.server 8000
```

Visit `http://localhost:8000` in your browser.

## Deployment

This site is set up to work well with **GitHub Pages**:

1. Go to the repo's **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`.
3. Choose the `main` branch and `/ (root)` folder, then save.
4. GitHub will publish the site at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Adding a new project

1. Add its thumbnail image to `assets/`.
2. Copy one of the files in `projects/` as a template and update the title, description, and links.
3. Add a new card to the **Projects** section in `index.html` linking to the new page.

## Contact

Feel free to reach out at [fullaondo.pia@gmail.com](mailto:fullaondo.pia@gmail.com).
