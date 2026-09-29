# Working instructions

- Treat this folder as the source project for *Electronic Trends*, the ECE department magazine at St. Thomas' College of Engineering & Technology.
- Preserve the confirmed issue identity: Volume X, 2025–26. Correct any stale Volume IX references when editing magazine material.
- Follow the folder map and LaTeX build guidance in the root `README.md`. Keep article sources, front matter, events, activities, assets, submissions, and build output in their current categories; update LaTeX paths whenever files move.
- Keep `.gitignore` aligned with generated LaTeX output and local editor/OS clutter. Do not ignore submitted source material or reviewed publication PDFs by default.
- Publication PDFs exceed GitHub's regular 100 MB file limit; commit the `*.pdf` Git LFS attributes before commits that add PDFs, and migrate already committed PDF history when needed before pushing.
- For every new instruction the user gives in this project, update both `AGENT.md` and `CONTEXT.md`: add durable working guidance here when appropriate, and record the request, relevant decision, and outcome in `CONTEXT.md`.
- Before starting work in a later session, read this file and `CONTEXT.md` for the accumulated instructions and project context.
- Keep `CONTEXT.md` as a concise, current handoff; update or consolidate it as work progresses.
