# Further reading

Everything the slides of *Modern Enterprise Architecture v2: Architecting for humans* (iSAQB Software Architecture Gathering, Berlin, November 2026) cite, what each source says, and where to read it: a free copy if there is one, otherwise a library loan on archive.org, otherwise the publisher or a shop.

Sections follow the talk's three parts. Only slides we show are covered: skipped slides are left out. Each entry lists the slide headlines it appears under, not slide numbers, so the list survives re-ordering.

`index.html` is the whole page: static, no build step needed to host it.

To change an entry, edit `sources.py` (the text and links) or `template.html` (the look), then:

```
python3 build.py
```

Link kinds in `sources.py` (as in the pizza-party and context-engineering lists):
- `free(url)`: open-access copy (a university or author's site, arXiv, Project Gutenberg, a full archive.org scan, a Wayback Machine capture of a legitimate page)
- `web(url)` / `yt(id, t=seconds)`: a free web page or video
- `ia(identifier)`: archive.org lending library (free account; checked that the item is in `inlibrary`, not only `printdisabled`)
- `doi(doi)` / `paid(url)`: publisher or subscription, usually paywalled
- `shop(url)` / `amazon(query)`: a shop; the amazon.de links are plain searches, not affiliate links

Order of links in an entry: a free copy or an archive.org loan first, then the publisher or a shop.

## Conventions

- **The citation follows the source, not the slide.** Where a slide has a different date, title or wording, the caveat says so. Fix the slide or keep the caveat, but don't copy the slide's version back in.
- **Caveats are for the reader**: a quote transcribed from audio, a line that is someone's summary, a quote we couldn't find word for word, one firm's account at one date.
- **Only what's on the slides.** Sources that are only in the speaker notes are left out.
- Publisher copies in `../sources/restricted-copies/` are not linked or published here.

## Hosting on GitHub Pages

As for the other two lists: create a public repository (e.g. `modern-enterprise-architecture-reading`), upload `index.html`, then Settings → Pages → Deploy from a branch → `main` / root. It appears at `https://simonrrr.github.io/modern-enterprise-architecture-reading/`.
