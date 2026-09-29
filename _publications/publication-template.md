---
# Keep this file as a starting point for future entries.
# Set `published: true` after replacing the placeholders below.
published: false

title: "Publication Title"
collection: publications
category: conferences        # books | manuscripts | conferences (see _config.yml)
permalink: /publication/publication-title
excerpt: "One- or two-sentence summary, used for page metadata."
date: 2026-01-01
venue: "Full Journal / Conference / Workshop Name"

# Fields used by the compact listing on the Publications page.
venue_short: "Venue'26"      # short tag shown in the left column; defaults to the year
authors: "Author One, **Your Name**, and Author Three."   # ** ** bolds your own name
notes:                       # optional extra lines: status, earlier versions, etc.
  - "Under review at *Journal Name*."
  - "Early version accepted to Workshop Name, 2025."
award: "**1st place**, Some Student Paper Competition."   # optional, slightly emphasised

# Optional links. Remove any field you do not need.
# `paperurl` is what the title links to; without it the title links to this page.
paperurl: https://arxiv.org/abs/1234.56789
slidesurl: /files/slides.pdf
bibtexurl: /files/bibtex.bib
codeurl: https://github.com/your-username/project-name
doi: 10.0000/example-doi

# Full citation, kept for reference and for the dedicated publication page.
citation: 'Author One, Author Two, and Author Three. (2026). "Publication Title." <i>Venue Name</i>.'
---

Replace this body text with any details you want on the dedicated publication page.
Note that when `paperurl` is set the listing links straight to the paper, so this
page is not linked from the Publications list.

Suggested workflow:

1. Duplicate this file.
2. Rename it to something descriptive, for example `2026-01-01-my-paper.md`.
3. Update the front matter fields.
4. Set `published: true`.
5. Add any linked assets under `/files` if needed.
