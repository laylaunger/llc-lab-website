# Language, Learning & Cognition Lab website

Initial Quarto scaffold for a GitHub Pages lab website.

## Pages

- Home
- Research
- People
- Publications
- Participate
- Join the Lab

## Preview locally

1. Install Quarto: https://quarto.org/docs/get-started/
2. Open a terminal in this folder.
3. Run:

   ```bash
   quarto preview
   ```

Quarto will open a local browser preview and update it as files change.

## Render

```bash
quarto render
```

The rendered website will be written to `docs/`.

## Publish with GitHub Pages (simple first setup)

This scaffold uses Quarto's `docs/` publishing method.

1. Create a GitHub repository and push this folder to its `main` branch.
2. Run `quarto render`, then commit and push the generated `docs/` folder.
3. In the GitHub repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Choose branch **main** and folder **/docs**.
6. Save.

GitHub Pages will then serve the site. A custom domain can be connected later.

## Current design status

- The logo image is a placeholder raster crop of the current preferred concept.
- Final logo should eventually be recreated/exported as SVG.
- Fonts are intentionally provisional.
- A research-derived homepage visual can be inserted later.
