# presentation-frameworks-evaluation
Test repository to check out different Markdown-based presentation frameworks. Below you can find a short write-up of my findings.

## Remark.js

- Markdown-based but everything is stored in an HTML file
- Use Remarker (https://github.com/kt3k/remarker) to separate CSS and Markdown
- Supports two-column layouts without much effort:
    - .leftCol[something]
    - .rightCol[something]
    - where something is parsed Markdown
- Generate presentation on the fly with Remarkise (https://remarkjs.com/remarkise)
- Export to PDF without a browser supported with DeckTape (https://github.com/astefanutti/decktape)
- Simply open the html file in a recent browser (Chrome is most supported for the moment)
- Supports code highlighting
- Does not support vertical slides
- Does not support integration of live Jupyter notebooks

## Reveal.js

- HTML-based
- Supports two-column layouts with custom CSS
- Can be served via GitHub Pages for a repository
- Export to PDF without a browser supported with DeckTape (https://github.com/astefanutti/decktape)
- Basic support by opening the html file in a recent browser (Chrome is most supported for the moment)
- Supports code highlighting
- Supports vertical slides
- Supports a lot of different plugins
- Vibrant community

## GitPitch

- Markdown-based
- Does not support two-column layouts directly
    - One could use custom HTML <div>s but the then content of the <div>s is not parsed
- Generates presentation on the fly from a GitHub repository
- Directly supports PDF export (but not without browser)
- Only on the paid tiers: Download presentation for offline mode
- Supports code highlighting
- Does not support vertical slides

## Marp

- Markdown-based editor with preview for slides
- Does not support two-column layouts directly
    - One could use custom HTML <div>s but the then content of the <div>s is not parsed
- Can directly generate a PDF version
- Directly supports PDF export (but not without browser) from the application
- Supports code highlighting
- Supports vertical slides
- Integrates well with e.g. GitPitch since the interpretation of the Markdown files is mostly compatible
