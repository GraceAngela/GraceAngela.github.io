# Grace Angela — Portfolio

Personal portfolio site, hosted free on GitHub Pages.

| Page | URL | File |
|---|---|---|
| Engineering portfolio | https://graceangela.github.io/ | `index.html` |
| Design portfolio | https://graceangela.github.io/design/ | `design/index.html` |

Each page is a single self-contained HTML file: its content, styles and script are all inside it. There is no build step.

## Edit the site in your browser

1. Open the page with `#edit` at the end of the address, for example
   `https://graceangela.github.io/#edit` or `https://graceangela.github.io/design/#edit`.
   (If the bar doesn't appear, refresh the page once.)
2. Click **Edit page** in the bar at the bottom.
3. Click any text to change it. Use **+ Add**, **Remove**, **↑ ↓** for list items, **Add photo**, and on the design page **+ Add images** for project photos.
4. Click **Download updated page**. Your browser saves a file called `index.html`.
5. On GitHub, open the repository and go to the matching file
   (`index.html` for the engineering page, `design/index.html` for the design page).
6. Click **Add file → Upload files**, drag in the downloaded `index.html` (for the design page, open the `design` folder first), and click **Commit changes**.
7. The live site updates in about a minute.

Edit mode only changes the copy in your own browser. Visitors never see it, and it can't change the live site until you upload the file.

**Tips**
- Images are resized and stored inside the page. A handful of photos per project is fine; very many large photos will make the page slow.
- To undo a change, open the file's **History** on GitHub and restore an earlier version.
- For bigger changes (new sections, layout or colour changes), give the HTML file to Claude and describe what you want.

## How it's built

- Content lives as JSON in `<script id="state">` near the end of each file; the page renders from it.
- Fonts come from Google Fonts: League Spartan, Hanken Grotesk and Newsreader (engineering); Bricolage Grotesque, Atkinson Hyperlegible and DM Mono (design).
- Light and dark mode follow the visitor's system setting.
