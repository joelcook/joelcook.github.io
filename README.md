# Joel Cook

Personal site: **I build AI and software that make vendor bills disappear.**

Static HTML on GitHub Pages. No build step or JavaScript dependency.

## Local preview

From this directory, run `python3 -m http.server 8080`, then visit
`http://localhost:8080`. Serve the root so absolute links work.

## Writing

Write like America.gov’s release notes and the National Design Studio
(decided 2026-10-24).

- The title is the result, in numbers: “Hosting: $50,000 down to $8,000.”
- One line under it says what it is.
- Lead with big before → after numbers (the stat tiles).
- Show any comparison as a chart: the result in blue, the rest in gray, every
  bar labeled with its value.
- Then short sections with plain labels (What changed, How it works, What’s
  next), one or two sentences or a few bullets each. “I” or “we” for what was
  done, “you” for what the reader can do.
- No backstory, no rhetoric, no hype. Method and caveats go in a small note at
  the bottom.

The numbers stay real. No invented figures, events, or quotes, and a sample
is never a full-scale claim.

When adding or changing an article, update its metadata, the homepage feature
if appropriate, `blog/index.html`, `feed.xml`, and `sitemap.xml`. Keep
existing article URLs and original publication dates.
