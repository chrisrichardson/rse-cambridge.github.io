---
title: How to use
permalink: /howto
menu: false
---

# Publishing pages

Each page that is to be published on the website should contain (at least) the
5 lines on the top of this file (if reading this file raw) or shown below,
including the triple dashed line, at the top of the file. Web pages should be
submitted in the `_pages` directory to prevent clutter, and should be in
MarkDown (`.md`) format.

Also note that the main page is the README.md file in the repository root.

```
---
title: Page title
permalink: /address
menu: true
---
```

## Keywords:

 - title: Page title as shown in the menu
 - permalink: permalink to the page, e.g. setting this to /pagename will set the
	 page URL to rse-cambridge.github.io/pagename
 - menu: set this to `true` to show a page in the web menu, false to keep it
	 hidden

## WIP
This is all work in progress and subject to change.
