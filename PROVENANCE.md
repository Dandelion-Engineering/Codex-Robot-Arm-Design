# File provenance

This repository starts with fresh history and curated copies from the original robot-arm project. Commit identifiers below identify the source history; that history is not included here.

- R300 baseline CAD: `e6b570b`.
- Completed R300B CAD, pickup pose and design documents: `cc9020d`.
- Original editable payload cases and numerical evidence: `ee20641`.
- The README’s three task excerpts match the original open-task commits `f4205b5`, `19e5f07` and `69f9638`. The project definition was checked against `5ac6237`.

[provenance.csv](provenance.csv) records source-relative paths, full source commit identifiers and SHA-256 checksums before and after curation. Images are unchanged copies; the initial-layout screenshot was visually inspected and contains only FreeCAD project UI, without personal or private UI details.

Only the FEM solver `WorkingDir` path was cleared in the four native project copies. All archive entries other than `Document.xml` are byte-identical, and that XML differs only in the single saved directory value. No geometry, mesh, material, constraint, force, solver setting or result was changed. The local FreeCAD installation directory was removed from dependency metadata. The native projects are self-contained; choose an explicit writable working directory before rerunning.

Archive CRC checks, XML parsing, file checksums, local Markdown links, repository size and a scan for incidental local paths and credentials were checked during curation. No new GUI or solver test was performed. The included reopen/rerun evidence belongs to the original study.
