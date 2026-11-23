# timothybaine.github.io

Source for [timothybaine.github.io](https://timothybaine.github.io), my personal site.

It's one static page: `index.html` with inline CSS and JavaScript, plus `images/IMG_4951.jpeg`. There's no build step and no dependencies apart from Google Fonts.

- The hero chart is a seeded, simulated two-regime price path drawn in the browser. It isn't market data.
- The "Recently on GitHub" section calls the public GitHub API when the page loads and falls back to a plain link if the API is unavailable.
- Light and dark themes follow the system setting. The toggle remembers your choice in this browser.

To preview locally:

```bash
python3 -m http.server 8000
```
