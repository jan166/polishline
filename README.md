# Polishline — landing page

A single self-contained `index.html`: all CSS, JS and logo artwork are inlined.
The only external request is Google Fonts.

Published with GitHub Pages from `main` at the repository root.

## Editing

The page carries its own editor. Open `index.html` from disk and an **Edit mode**
button appears at the bottom right; on the published site it stays hidden, and
`#edit` in the URL opens it anywhere.

In edit mode you can

- reorder or hide any block, by drag or by the arrows in the layout panel
- edit any wording directly on the page
- **Save** to write the file back (Chrome) or download it, and **Copy** to take
  the whole HTML to the clipboard

Wording, block order and hidden blocks are stored as a patch in the page's
`pl-data` script. The authored markup itself is never rewritten, so saving
repeatedly does not degrade the file.

`#clean` hides the edit button anywhere, for a screenshot.
