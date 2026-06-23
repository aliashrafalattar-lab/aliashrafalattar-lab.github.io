# Ali Alattar — Personal Website

Source for my personal research portfolio site. It is a single, self-contained static
page (no build step, no framework). Styling and scripts are inline in `index.html`; the
only external dependency is Google Fonts.

## Structure

```
index.html                                  Single-page site (HTML + inline CSS/JS)
HeadShot.jpg                                 Portrait used in the About section / social preview
Ali_Alattar_CV.pdf                           Résumé linked from the nav, hero, and contact
assets/
  protein-interface-hero.webp               Hero line-art illustration
  CapstoneProject_AlattarAli_v10.pdf         Capstone proposal linked from the research section
```

## View locally

Open `index.html` directly in a browser, or serve the folder so relative links resolve:

```bash
npx http-server -p 8080 -c-1
# then open http://127.0.0.1:8080/
```

## Deploy with GitHub Pages

1. Push this folder to a GitHub repository.
2. In **Settings → Pages**, set the source to the `main` branch, root folder.
3. The site publishes at `https://<username>.github.io/<repo>/`.

For a user/organization site served at `https://<username>.github.io/`, name the repository
`<username>.github.io`. The `.nojekyll` file tells GitHub Pages to serve the files as-is.
