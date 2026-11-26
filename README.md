# SAMAKI Viewer

A single-page, static viewer for the SAMAKI aquaculture installation diagrams. The page includes six interactive figures, presentation controls, and SVG/PNG downloads. It has no build step or runtime dependencies; fonts and diagram artwork are embedded in the HTML.

## View locally

Open [`index.html`](index.html) in a modern browser.

## Deploy with Vercel

Import the repository into Vercel and deploy from the repository root. This is a static site: choose **Other** if asked for a framework, and leave the build command empty. Vercel serves `index.html` from the root as the site homepage; no build configuration or runtime dependencies are needed.

## Publish with GitHub Pages

In the repository, open **Settings → Pages**, choose **Deploy from a branch**, and select the branch containing these files and the `/ (root)` folder. The site homepage will be `https://<owner>.github.io/<repository>/`.

## Repository contents

- `index.html` — standalone viewer page and deployment homepage.
- `fig*.png` — PNG figure exports.
