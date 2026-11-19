# World War II

A single-page encyclopedia article about the Second World War.

Open `index.html` in a browser. There is nothing to build and nothing to install:
the page is one self-contained file with no external assets, fonts or network
requests. The photographs are drawn in the browser when the page loads.

Read it from the top, in order, and take your time.

## Notes for whoever maintains this

- It is fiction. The history in the first half is accurate; the article stops
  being reliable somewhere around 1941 and does not recover. Nothing in it is a
  jump scare and it makes no sound.
- The page remembers whether you finished it (one `localStorage` key,
  `omnipedia.watch`, never sent anywhere). Open `index.html?reset` to clear it.
- After the ending the browser will ask for confirmation before the tab closes.
  That is deliberate.
- The Article, Talk, View source and View history tabs all work.
- To publish it, enable GitHub Pages for this repository (Settings → Pages →
  deploy from the default branch, root folder).
