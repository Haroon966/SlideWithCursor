# SlideWithCursor

Presentations built with HTML, CSS, and JavaScript, hosted on GitHub Pages.

**Live site:** `https://haroon966.github.io/SlideWithCursor/`

## Presentations

- [Planets](planets/) — A quick tour of the solar system
- [UI & UX design](ui-ux-design/) — Principles and practices for better products
- [React & Django intro](react-django-intro/) — Intro to React and Django

## Enabling GitHub Pages

1. Open your repo on GitHub → **Settings** → **Pages**.
2. Under **Source**, choose **Deploy from a branch**.
3. Select branch **main** (or **master**) and folder **/ (root)**.
4. Save. The site will be available at `https://<username>.github.io/SlideWithCursor/` after the build finishes.

## Adding a new presentation

1. Create a new folder, e.g. `my-topic/`.
2. Add `my-topic/index.html` with your slides. Use `<section class="slide">` for each slide and the same navigation script (Previous/Next buttons and arrow keys) as in the existing presentations if you want the same behavior.
3. Add a link on the home page ([index.html](index.html)) in the list of presentations, e.g. `<a href="my-topic/">My topic</a>`.

Use **relative** paths (e.g. `planets/`, `../`) so links work on GitHub Pages.
