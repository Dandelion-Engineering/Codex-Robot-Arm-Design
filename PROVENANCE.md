# File provenance

This repository starts with fresh history and curated copies from the original robot-arm project. Commit identifiers below identify the source history; that history is not included here.

- R300 baseline CAD: `e6b570b`.
- Completed R300B CAD, pickup pose and design documents: `cc9020d`.
- Original editable payload cases and numerical evidence: `ee20641`.
- Task prose compared against original open-task commits `f4205b5`, `19e5f07` and `69f9638`; project definition verified against `5ac6237`. The supplied README contains one existing encoding artifact in the first task: the apostrophe in "There's" appears as three mojibake characters. It is preserved because the approved draft was to be copied unchanged. All other task prose matches.
- The supplied README is byte-identical to the approved draft, SHA-256 `78d53f84d364fe4ba5d62b58ce8797867664ada9d6f58cd975d67937774fbe17`.

[provenance.csv](provenance.csv) records source-relative paths, full source commit identifiers and SHA-256 checksums before and after curation. Images are unchanged copies; the initial-layout screenshot was visually inspected and contains only FreeCAD project UI, without personal or private UI details.

Only the FEM solver `WorkingDir` path was cleared in the four native project copies. All archive entries other than `Document.xml` are byte-identical, and that XML differs only in the single saved directory value. No geometry, mesh, material, constraint, force, solver setting or result was changed. The local FreeCAD installation directory was removed from dependency metadata. The native projects are self-contained; choose an explicit writable working directory before rerunning.

Archive CRC checks, XML parsing, file checksums, local Markdown links, repository size and a scan for incidental local paths and credentials were checked during curation. No new GUI or solver test was performed. The included reopen/rerun evidence belongs to the original study.
