# AGENTS.md

## Scope

These instructions apply to `mathematical_lectures/mathematical_stories/` and all of its descendants.

## Editorial purpose

The lecture is written as a logically ordered mathematical story. Concepts must appear only after the geometric or algebraic objects needed to define them have been introduced. Do not use later machinery merely because it shortens an earlier argument. In particular, preserve the intended order of Euclidean constructions, Cartesian coordinates, vectors, lines, planes, and later analytic tools.

The PDF has two simultaneous uses. During a lecture it must make the conceptual core immediately visible. After the lecture it must remain a self-contained source from which a student can recover the complete argument without searching elsewhere. Do not remove necessary derivations merely to shorten the document; instead distinguish the role of each block visually.

## Information hierarchy

Use the established environments consistently:

- `corebox` for the central idea, indispensable interpretation, or minimal knowledge that should remain after the lecture;
- `definitionbox` for definitions and canonical formulas that define an object;
- `theorembox` for theorems, criteria, and reusable mathematical results;
- `examplebox` for every worked example;
- `derivationbox` for calculations that derive a formula from earlier geometric or algebraic conditions;
- `proofbox` for proofs or explicit verification of a stated result;
- `interpretationbox` for the geometric or conceptual meaning of a formula;
- `remarkbox` for cautions, exceptions, and secondary comments;
- `summarybox` for a compact comparison or end-of-section synthesis.

Do not place every paragraph in a box. Narrative transitions and short motivation remain ordinary prose. The boxes identify function and priority; they must not become decorative noise.

## Source structure

Use the following hierarchy:

1. `chapters/chapter_XX.tex` contains the chapter heading, chapter-local TikZ settings, and `\input` statements for active sections.
2. Every substantial `\section` has its own directory under the corresponding chapter directory.
3. The directory contains `section.tex`, which holds the `\section{...}` heading, a short section introduction when appropriate, and ordered `\input` statements.
4. Each substantial `\subsection` belongs in its own descriptively named `.tex` file.
5. Keep short, tightly coupled `\subsubsection` blocks together. Give a long or independently edited construction, proof, derivation, worked example, or TikZ diagram its own file.
6. Use lowercase snake_case file and directory names. Names must describe mathematical content, not revision history. Do not create names such as `revised`, `new`, `final`, or `copy`.

## Editing rules

- Change only the requested mathematical or graphical unit.
- Do not silently rewrite nearby prose while performing a structural move.
- Structural refactors must preserve source text byte-for-byte as far as practical, except for `\input` boundaries and final newlines.
- Never combine a structural migration with a mathematical correction in the same commit.
- Before editing, identify the active `\input` chain from `main.tex` to the target file.
- Do not edit inactive alternatives or generated artifacts.
- Do not introduce vectors into material that precedes the vector chapter.
- A right angle may be used as a Euclidean construction before numerical angle measure is introduced.
- Every worked example must be visibly marked as an example.
- A derivation must end in a visibly marked definition, theorem, or core formula when the resulting statement is intended for later use.

## TikZ rules

- Keep coordinate axes visually distinct from the geometric object under discussion.
- Construction stages should be distinguishable by line style or colour when this explains the construction.
- Keep colours consistent across iterations of the same diagram.
- Avoid labels overlapping paths, points, or one another.
- Do not change global TikZ styles to fix one local figure unless explicitly requested.

## Safe migration workflow

For each source file being split:

1. Read the complete active source file.
2. Record all `\section`, `\subsection`, and `\subsubsection` boundaries.
3. Create the destination directory and new files while leaving the old source in place.
4. Create or update `section.tex` so the concatenated `\input` order matches the original order exactly.
5. Update the parent chapter file to point to the new `section.tex`.
6. Verify every original heading and content block appears exactly once in the new active input graph.
7. Build the PDF or run the repository's existing CI build.
8. Remove the old monolithic source only after the new input graph is verified.
9. Build again and inspect the commit diff.

## Validation

A structural commit is complete only when:

- all referenced `\input` targets exist;
- no migrated content remains active twice;
- the old monolithic file is no longer referenced;
- the PDF build succeeds, when build infrastructure is available;
- the diff contains no unrelated prose or mathematical changes.

## Generated files

Do not manually edit generated PDFs, auxiliary LaTeX files, logs, or temporary build outputs. Source changes belong in `.tex`, style, macro, build, or documentation files.
