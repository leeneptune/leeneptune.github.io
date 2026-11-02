my website :P

## Updating

- **Add a project:** copy a `<dt>`/`<dd>` pair in `index.html` (and `projects.html`).
- **Add news:** copy an `<li>` in `index.html` (and `news.html`). Update the ticker too.
- **Change links, bookmarks, cool stuff:** edit the matching box in `index.html`.
- **Change the look:** edit `style.css`.
- The header, nav, and footer are copied into every page, so a nav change means editing all six HTML files.

## To do

The site is raw HTML right now. That's fine for a handful of entries, but it won't
scale: every new project or news item is a copy-and-paste in two or three places,
and the shared header/footer has to be kept in sync by hand across six files.

At some point we should improve the site to support content additions in a
sustainable way:

- Add an entry once, in one place, and have it show up everywhere it belongs
  (home page, section page, ticker).
- Pull content from a database or data file instead of hard-coding it in HTML.
- Share the header, nav, and footer so they're defined once.

Whatever we pick, the goal is to keep the page itself as simple as it is now:
plain HTML output, no front-end framework, nothing heavy.
