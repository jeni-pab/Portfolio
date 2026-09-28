# Portfolio Site

This project is a static portfolio page built with plain HTML and CSS.

## Run locally

From the project folder:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy to GitHub Pages

1. Push this folder to a GitHub repository.
2. In GitHub, open the repository.
3. Go to Settings → Pages.
4. Under Source, select the default branch (for example `main`).
5. Keep the folder as `/root`.
6. Save.

GitHub Pages will publish the site at a URL like:

```text
https://<your-username>.github.io/<repository-name>/
```

## Notes

- No build step is required because the site is plain HTML/CSS.
- A `.nojekyll` file is included so GitHub Pages does not process the site with Jekyll.
