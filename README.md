# SAMAKI Viewer

A single-page, static viewer for the SAMAKI aquaculture installation diagrams. The page includes six interactive figures, presentation controls, and SVG/PNG downloads. It has no build step or runtime dependencies; fonts and diagram artwork are embedded in the HTML.

## View locally

Open [`samaki-viewer-v5.html`](samaki-viewer-v5.html) in a modern browser.

## Publish with GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select the branch containing these files and the `/ (root)` folder, then save.
4. Open the published site at `https://<owner>.github.io/<repository>/samaki-viewer-v5.html`.

To serve the viewer from the site root instead, rename `samaki-viewer-v5.html` to `index.html` before publishing.

## Repository contents

- `samaki-viewer-v5.html` — standalone viewer page.
- `fig*.png` — PNG figure exports.
