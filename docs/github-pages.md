# Publish the Novera showcase with GitHub Pages

The public showcase repository is `ezequiel-gb/Novera`. Its root `index.html` and both standalone explorers use relative asset paths and ordinary HTML, CSS and JavaScript.

## Target URLs

After publication and Pages deployment:

- Landing page: `https://ezequiel-gb.github.io/Novera/`
- English explorer: `https://ezequiel-gb.github.io/Novera/docs/architecture-explorer/Novera-Architecture-Explorer-EN.html`
- Spanish explorer: `https://ezequiel-gb.github.io/Novera/docs/architecture-explorer/Novera-Architecture-Explorer-ES.html`

## Pages settings

After the repository is created and its reviewed `main` branch is pushed, open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**, choose `main` and `/(root)`, and save. GitHub Pages then serves the static landing page and explorers. The site is public; the private Core repository is separate and must not be used as the Pages source.

## Verify the live site

1. Open the canonical URL shown in repository settings.
2. Check the logo, landing images and both language links.
3. Select components, use orbit/zoom/pan/reset, and switch to the accessible 2D view.
4. Advance and reset guided workflows in English and Spanish.
5. Check desktop and mobile widths and confirm there are no browser errors or external requests.
6. Confirm every displayed example remains synthetic.

GitHub does not execute JavaScript inside a README. The README links to the Pages experience; the interactive features run on the published static site.
