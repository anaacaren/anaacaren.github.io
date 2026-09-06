# Portfolio

A responsive, accessible one-page portfolio built from the experience.

The site is plain HTML, CSS, and JavaScript, so GitHub Pages can publish it directly from the repository root without a build step.

You like it? Feel free to copy <3

## Run locally

No installation or build step is required. Clone the repository and enter its directory:

```bash
git clone https://github.com/anaacaren/anaacaren.github.io.git
cd anaacaren.github.io
```

You can open `index.html` directly in a browser. For a more accurate local preview, start a small web server with Python:

```bash
python -m http.server 8000
```

On Windows, if the `python` command is unavailable, try:

```powershell
py -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000). Press `Ctrl+C` in the terminal to stop the server.

## Project files

- `index.html` contains the page content and structure.
- `styles.css` contains the main visual design and responsive layout.
- `orbit.css` styles the rotating text around the AI emblem.
- `script.js` provides the mobile menu and scroll animations.
