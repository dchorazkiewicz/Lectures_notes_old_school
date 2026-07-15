# Mathematical Stories source-structure migration

Branch: `refactor/mathematical-stories-structure`

## Goal

Replace large monolithic section files with a stable hierarchy in which each substantial section owns a directory and each substantial subsection is independently editable, without changing mathematical content or PDF ordering.

## Invariants

- Preserve the active order of all headings, paragraphs, equations, boxes, and TikZ figures.
- Do not make mathematical or stylistic revisions during file moves.
- Keep every migration reviewable as a separate commit.
- Do not delete an old source file until its replacement input graph has been checked.
- Use descriptive names without revision suffixes.

## Stages

- [x] Create refactor branch.
- [x] Add `AGENTS.md` with editorial, structural, TikZ, and validation rules.
- [x] Split Chapter 1 Euclidean prerequisites into one section directory and subsection files.
- [x] Split Chapter 1 Cartesian-coordinate construction into one section directory and subsection files.
- [x] Move the Chapter 1 polar-coordinate section into its own directory. It has no `\subsection` headings, so its text remains one file.
- [x] Split Chapter 2 vector section into one section directory and subsection files.
- [ ] Move line, plane, conic, and quadric sources into the chapter directories that actually include them.
- [ ] Audit remaining active chapter sources and split only files that are still too large for safe focused editing.
- [x] Remove the superseded Chapter 1 and Chapter 2 monolithic sources after input-graph verification.
- [ ] Run the PDF build in CI. The repository build workflow is manual-dispatch only and local checkout was unavailable because the execution environment could not resolve `github.com`.
- [ ] Compare the branch with `main` and open a draft pull request.

## Target convention

```text
chapters/
  chapter_XX.tex
  chapter_XX/
    descriptive_section_name/
      section.tex
      descriptive_subsection_name.tex
```

Long independently edited constructions may use another directory level:

```text
derived_constructions/
  subsection.tex
  perpendicular_bisector.tex
  perpendicular_on_line.tex
  perpendicular_outside_line.tex
  angle_bisector.tex
  parallel_through_point.tex
```

## Validation checklist for every stage

- [x] Parent `\input` points to the new section entry file for the migrated Chapter 1 and Chapter 2 sections.
- [x] Every new `\input` target was created before the parent was switched.
- [x] Heading order follows the old monolithic files.
- [x] No migrated source remains active twice.
- [x] Old migrated sources were unreferenced before deletion.
- [x] Structural commits were kept separate from mathematical editing.
- [ ] PDF build succeeds in GitHub Actions.
