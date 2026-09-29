# Project context and handoff

## Project

This workspace contains the production files for Volume X (2025–26) of *Electronic Trends*, the Electronics & Communication Engineering department magazine of St. Thomas' College of Engineering & Technology, Kolkata.

- `Latex/main.tex` is the LaTeX entry point. It assembles the cover, editorial pages and messages, vision and mission, contents, reports, events, puzzles, and answers.
- `Latex/sections/front_matter/` holds cover, editorial, message, vision and mission, and contents design source files.
- `Latex/sections/reports/reports.tex` orders 17 faculty and student articles; Report 1, “Next-Generation Networking and Communication Protocols for IoT,” is `Latex/sections/reports/Faculty(PC).tex`.
- `Latex/sections/events/` contains three department event reports. `Latex/sections/activities/` contains puzzles and answers.
- `Latex/assets/images/` contains placed images and diagrams; `Latex/submissions/prism-uploads/` contains submitted drafts and source material.
- `Latex/build/` is the target for generated LaTeX auxiliary files and text extraction. The current compiled `Latex/main.pdf` remains at the LaTeX root because it is locked; build from `Latex/` with the commands in the root `README.md` to direct new output into `build/`.
- `PDF/` contains merged issue PDFs and cover/back-page PDFs. `Word/` contains editable cover and back-page documents.
- `Latex/main.pdf` is the compiled issue; `Latex/main.txt` is its text extraction. `PDF/main.pdf` is a copy of the compiled issue.

## Confirmed instructions and work

- The issue is Volume X. If Volume IX appears in magazine content, change it to Volume X.
- Refreshed the stale text extraction from the current compiled PDF; it is now `Latex/build/main.txt`. The magazine source (`Latex/sections/front_matter/message_head.tex`) and current compiled PDFs already identify the issue as Volume X; no Volume IX occurrence was found in the checked issue PDFs.
- Organized LaTeX source files into front matter, reports, events, and activities; moved placed images into `Latex/assets/images/`, submitted source material into `Latex/submissions/prism-uploads/`, and auxiliary files into `Latex/build/`. Updated source include and image paths to match. The open/locked `Latex/main.pdf` remains at the LaTeX root; the publication PDF copies remain in `PDF/`.
- Added root `README.md` with the folder map and build steps. The magazine was not recompiled during the restructure.
- Added root `.gitignore` for LaTeX build products and common local editor/OS files; publication PDFs and submitted material remain eligible for version control.
- User requested the PDF LFS tracking commit be pushed before the report/project commit. Prepared to place `Track PDFs with Git LFS` first and `main report added` second, on top of the current `origin/main` history so both pushes can be fast-forwards. Existing rewritten history is preserved on `backup/main-before-lfs-commit-order`; the original pre-migration history is preserved on `backup/main-before-pdf-lfs`.
- The user clarified that the persistent project handoff must be named `CONTEXT.md` (not `CONTENT.md`). Continue maintaining this file and `AGENT.md` for each new instruction.
