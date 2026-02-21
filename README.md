# SlideWithCursor

Presentations built with HTML, CSS, and JavaScript, hosted on GitHub Pages.

**Live site:** `https://haroon966.github.io/SlideWithCursor/`

## Presentations

- [Planets](planets/) — A quick tour of the solar system
- [UI & UX design](ui-ux-design/) — Principles and practices for better products
- [React & Django intro](react-django-intro/) — Intro to React and Django

When your changes are on the `main` branch, your presentation links will appear on the home page. You can click a link to open that presentation, or share the link with others so they can view it too.

## How to make presentations

1. **Create a folder** for your presentation, e.g. `my-topic/`.
2. **Add `index.html`** inside that folder. Copy the structure from an existing presentation (e.g. [planets/index.html](planets/index.html)):
   - Each slide is a `<section class="slide">` (give the first one `class="slide active"`).
   - Include the same **Previous / Next** buttons and the script at the bottom so arrow keys and Space work.
   - Add a “Back to presentations” link with `href="../"`.
3. **Link from the home page**: open [index.html](index.html) and add a new list item, e.g. `<li><a href="my-topic/">My topic</a></li>`.

Use **relative** paths only (e.g. `my-topic/`, `../`) so everything works on GitHub Pages.

## How to push your changes

1. **Clone the repo** (if you haven’t already):
   ```bash
   git clone https://github.com/Haroon966/SlideWithCursor.git
   cd SlideWithCursor
   ```

2. **After adding or editing presentations**, commit and push:
   ```bash
   git add .
   git commit -m "Add my presentation"
   git push origin main
   ```

3. If you use a **fork** or your **own repo**, set your remote and push there:
   ```bash
   git remote set-url origin https://github.com/YOUR_USERNAME/SlideWithCursor.git
   git push -u origin main
   ```
