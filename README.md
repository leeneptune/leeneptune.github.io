my website :P

## Updating

- **Add a project:** copy a `<dt>`/`<dd>` pair in `index.html` (and `projects.html`).
- **Add news:** copy an `<li>` in `index.html` (and `news.html`). Update the ticker too.
- **Change links, bookmarks, cool stuff:** edit the matching box in `index.html`.
- **Change the look:** edit `style.css`.
- **Add a fake ad:** copy an `<a class="ad">` in the banner block (it's in every page), add an `adN` style, and bump the three AD COUNT numbers in `style.css`.
- The header, nav, and footer are copied into every page, so a nav change means editing all six HTML files.

## Fun mode

The site is serious by default: no ads, popups, toys, ticker, or counter. Add `#fun` to the URL
(`leeneptune.github.io/#fun`, or the "Switch to fun mode" link in the footer) to turn all of that on. The nav
links keep you in whichever mode you're in. Anything marked `class="fun"` in the HTML only shows in fun mode.

## Easter eggs (fun mode, all CSS, no scripts)

The toys share hidden checkboxes at the top of `<body>`, so they can react to each other:

- Close the **Security Alert** popup and "Are you sure?" takes its place. Close that and a toolbar offer
  appears. Close that and it's over. Or install the toolbar: it "installs", shows up under the nav (its x
  removes it), and closing the finished install brings the Security Alert back one last time.
- The toolbar works, sort of: Search gives sponsored results and real site links, "+13 more" adds twelve search
  bars and a second weather widget, the weather widget jumps to the forecast, and the pop-up blocker blocks the popups.
- Press **LAUNCH** (once per visit): the ticker gets a BREAKING item, a "rocket insurance" ad joins the
  banner, and the popup's "Remind me in orbit" fires.

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
