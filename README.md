# openbeta

Portfolio site for openbeta.net. One static page, no build step.

- `index.html` is the whole site (HTML, CSS and JS).
- Projects and tracking live in Supabase (project `openbeta`). To add a project, insert a row into the `projects` table.
- Visits and card clicks are logged through the `track()` function. Open `openbeta.net/#me` once in a browser to stop counting your own visits there.
- `CNAME` tells GitHub Pages to serve this at openbeta.net.
