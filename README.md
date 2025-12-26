# html_files

A collection of static HTML files and small frontend examples. This repository contains pure HTML (and optional static assets like CSS/JS/images) intended for demos, prototypes, or learning purposes.

## Contents
- `index.html` — (recommended) main entry / demo page
- `examples/` — example pages and small demos
- `assets/` — images, CSS, and JavaScript used by the pages
- `README.md` — this file

(Actual filenames may vary — open the repository to see the exact structure.)

## Getting started (view locally)
1. Clone the repo:
   ```bash
   git clone https://github.com/DishiGpt/html_files.git
   cd html_files
   ```
2. Open a page:
   - Double click `index.html` (or any `.html`) to open in your browser, or
   - Use a local static server for a better development experience:
     - VS Code: install the [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension and click "Go Live".
     - Python 3: `python -m http.server 8000` then open `http://localhost:8000`.
     - Node: `npx http-server` (if http-server is available).

## Deploying (GitHub Pages)
1. Push the repository to GitHub.
2. In the repository Settings → Pages, set the source to the `main` (or `gh-pages`) branch and select the root `/` (or `docs/`) folder.
3. After a few minutes your static site will be available at `https://<username>.github.io/html_files` (or your configured URL).

## Contributing
- Small documentation, HTML fixes, or new example pages are welcome.
- Open a pull request with:
  - a short description of what you added/changed
  - preview screenshots (if applicable)
  - any steps to view/test the new page

Suggested branch name format: `feature/<short-description>`.

## Tips & Tools
- Editor: VS Code (with Live Server)
- Linter/formatter: Prettier for HTML/CSS/JS
- Use semantic HTML and keep assets organized under `assets/` or `static/`.

## License
This repository does not include a LICENSE file by default. If you intend to make the work open-source, add a LICENSE (for example, [MIT](https://opensource.org/licenses/MIT)).

## Contact
If you have questions or want to collaborate, open an issue or submit a pull request.
