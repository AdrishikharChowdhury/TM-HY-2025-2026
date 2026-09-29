# Electronic Trends — Volume X (2025–26)

This workspace contains the editable LaTeX magazine, source submissions, placed assets, and publication exports for the ECE department magazine at St. Thomas' College of Engineering & Technology.

## Folders

- `Latex/main.tex` — magazine entry point.
- `Latex/sections/front_matter/` — cover, messages, editorial board, and vision and mission pages.
- `Latex/sections/reports/` — the 17 articles and their supporting text snippets. Report 1 is `Faculty(PC).tex`.
- `Latex/sections/events/` — event reports.
- `Latex/sections/activities/` — puzzles and answer pages.
- `Latex/assets/images/` — images and diagrams placed in the magazine.
- `Latex/submissions/prism-uploads/` — original submitted files and drafts.
- `Latex/build/` — LaTeX auxiliary and text extraction files.
- `PDF/` — merged issue PDFs and PDF cover/back-page exports.
- `Word/` — editable cover and back-page documents.

## Build

Run the LaTeX build from the `Latex` directory so relative image paths resolve. For example, with pdfLaTeX:

```powershell
pdflatex -output-directory=build main.tex
pdflatex -output-directory=build main.tex
```

The second pass refreshes the table of contents and page references. Move or copy a reviewed output from `Latex/build/` into `PDF/` when preparing a publication export.

Read `AGENT.md` and `CONTEXT.md` before continuing work in a new session.
