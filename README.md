# prototype-at-scad.github.io

The website of Prototype, the typography club at SCAD Savannah.
Live at **https://prototype-at-scad.github.io**

## How to edit

You don't need to install anything. Edit right here on GitHub:

1. Open the file you want to change (list below).
2. Click the pencil icon, make your edit, then click **Commit changes**.
3. Wait a minute or two. The live site updates by itself.

| To change… | Edit this file |
| --- | --- |
| The home page | `index.md` |
| The workshop list | `workshops.md` |
| Bracket issues | `bracket.md` |
| Officers, faculty, about text | `about.md` |
| Colors and type | `assets/css/style.css` (the variables at the top) |
| Header, nav, footer | `_layouts/default.html` |

## Writing in Markdown

- `# Title` is the big page title; `## Section` is a section heading.
- `**bold**` for names and titles, `*italic*` for dates (they show in gray).
- `- ` at the start of a line makes a list item. Every list becomes ruled rows.
- `[link text](https://example.com)` makes a link.

## Adding a page

1. Create a new file, e.g. `events.md`, starting with:

   ```
   ---
   layout: default
   title: Events
   permalink: /events/
   ---
   ```

2. Add a link to it in the `<nav>` in `_layouts/default.html`.

Only add a page when there's content to keep it current.

## Fonts

Instrument Serif and Instrument Sans, under the SIL Open Font License (see `assets/fonts/`).
