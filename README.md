# dannyturkson.github.io

Personal academic website of Danny Turkson, Ph.D. Candidate in Economics at the University of North Carolina at Chapel Hill.

Built with Jekyll + Bootstrap 4. Adapted from the [kbconsult2017](https://github.com/kbconsult2017) template, which was itself adapted from Nathan B. Wikle's site design by Olivia Wikle.

## Structure

```
├── _config.yml          # Site settings (name, email, links)
├── _data/
│   └── nav_config.csv   # Navigation links
├── _includes/           # Reusable HTML partials (head, header, footer)
├── _layouts/
│   ├── default.html     # Base layout
│   └── page.html        # Two-column layout with sidebar
├── _sass/
│   └── _custom.scss     # Style overrides
├── assets/
│   └── css/custom.scss  # Main SCSS entry point (Jekyll compiles this)
├── images/
│   └── profile.JPG      # Your photo
├── files/               # PDFs (CV, papers, statements)
├── index.md             # About / Home
├── research.md
├── teaching.md
├── wbes.md
├── jobmarket.md
└── cv.md
```

## Setup

1. Push this folder to your `dannyturkson.github.io` repository.
2. GitHub Pages will build it automatically (no local Jekyll needed).
3. Update `_config.yml` with your real links.
4. Place your PDFs in `files/` and your photo at `images/profile.JPG`.
