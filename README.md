# Date Facts Agent

A single-file web app that explores a month/date using live Wikimedia data.

## Capabilities
- Birth month/date only; birth year is not required.
- Optional historical context year and context window.
- Live notable-birth retrieval from Wikimedia's On This Day feed.
- Intellectual/creative figure ranking.
- Person images and source links when available.
- Birthplace resolution through Wikidata.
- Regional history, education, school, and pedagogy searches through Wikipedia.
- "Know more" contextual search.
- No API key and no server required.

## Run
Open `index.html` directly, or serve the folder locally:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages
Commit `index.html` to a repository and enable GitHub Pages for the repository's main branch/root.

## Data note
The UI deliberately displays source-linked evidence rather than generating unsourced historical claims.
