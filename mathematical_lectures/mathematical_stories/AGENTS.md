# AGENTS.md

## Scope

These instructions apply to `mathematical_lectures/mathematical_stories/` and every file and directory below it.

This file is the founding editorial and working charter for the lecture. Read it before analysing, editing, restructuring, or extending any part of the lecture.

## Repository workflow

Work with this repository through the GitHub connector by default.

- Read repository files through the GitHub connector.
- Edit, create, move, or delete repository files through the GitHub connector.
- Do not invent an alternative repository workflow, local planning system, temporary mirror, or unrelated toolchain unless the user explicitly requests it.
- Do not modify generated PDFs, auxiliary LaTeX files, logs, or temporary build products.
- Before editing a mathematical unit, identify the active `\input` or `\include` chain that reaches it.
- Change only what the user requested. Do not silently improve neighbouring material.

## Structure of the lecture

The lecture currently consists of twelve numbered chapters.

The intended source hierarchy is:

1. `chapters/chapter_XX.tex` contains the chapter title, chapter-level settings, and the ordered `\input` statements for active sections.
2. Each substantial section belongs to its own directory inside the corresponding chapter directory.
3. A section directory contains `section.tex`, which holds the `\section{...}` heading and the ordered inputs for its contents.
4. Each substantial subsection, mathematical argument, example, construction, derivation, proof, or diagram should live in a small, descriptively named `.tex` file.
5. Files should remain small enough to read, review, and edit independently.
6. Use lowercase snake_case names that describe mathematical content. Do not use names such as `new`, `revised`, `final`, or `copy`.

The purpose of this structure is not bureaucracy. It exists so that a precise mathematical idea can be changed without rewriting an entire chapter or disturbing unrelated material.

## Authorial authority

The user is the author and lecturer. The lecture must express the user's mathematical viewpoint, priorities, rhythm, and teaching intention.

The assistant does not decide independently:

- what a chapter is fundamentally about;
- which ideas deserve emphasis;
- what order creates the intended mathematical tension;
- whether a chapter should begin with an example, theorem, construction, paradox, observation, question, or historical motivation;
- which results belong to the live lecture and which belong only to written reference material;
- what emotional or intellectual character a chapter should have.

Those decisions belong to the user. Do not replace them with a conventional textbook order, a generic curriculum, or an encyclopaedic survey.

When the user has not yet specified the intended character of a chapter or section, do not manufacture one. Wait for the user's direction, or provide analysis only when explicitly asked.

## Chapter intention comes first

Before substantial work begins on a chapter, the user will define what that chapter is meant to achieve.

The opening of each chapter is the governing statement for all later work in that chapter. It should record, in the user's terms:

- which ideas the chapter is meant to communicate;
- what the student should notice, understand, or be able to reconstruct;
- what mathematical viewpoint should remain after the lecture;
- which examples, questions, constructions, or applications should drive the story;
- what belongs to the essential lecture core;
- what may remain as supplementary or self-study material.

Treat this chapter intention as the primary editorial constraint. Definitions, theorems, examples, proofs, diagrams, and exercises must serve it. A mathematically correct passage that does not serve the stated intention may still be inappropriate for the chapter.

Do not write a chapter opening until the user has explained the intended chapter. Do not infer a generic list of learning outcomes from the existing contents.

## Mathematical storytelling

This lecture is not an encyclopaedia and must not read like a flat list of standard facts.

A chapter needs an intention, a point of view, and a reason for its order. Mathematical content should unfold as a story in which one idea creates the need for the next.

Avoid default textbook habits such as:

- beginning with a catalogue of definitions merely because they are standard;
- presenting every known criterion, equivalent formulation, or computational method at equal weight;
- adding material only to make the chapter appear complete;
- turning a central idea into a checklist of properties;
- replacing motivation with a conventional sequence of theorem--proof--example;
- treating all mathematically valid content as equally important;
- expanding a chapter into a survey when the lecture requires one clear idea.

The lecture may begin from a problem, construction, example, surprising obstruction, visual pattern, physical situation, or conceptual question. The correct opening and rhythm are determined by the user's declared intention for that chapter.

## Lecture scale and selection

Each numbered chapter is intended to support one lecture of two 45-minute parts unless the user states otherwise.

The written notes may contain more than can be presented live, but the live conceptual core must remain visible. Do not assume that every definition, theorem, proof, technique, classification, or application present in the source must be presented during the lecture.

When auditing scope, distinguish clearly between:

- the indispensable conceptual core;
- examples needed to make the idea visible;
- technical tools required for those examples;
- useful written reference material;
- optional extensions and self-study material.

Do not delete, compress, promote, or demote material solely on your own judgement unless the user explicitly asks for an audit or authorises the change.

## Editing discipline

- Follow the user's requested scope literally.
- Do not perform additional clean-up, rewriting, reordering, or stylistic harmonisation without permission.
- Do not convert the user's distinctive mathematical narrative into neutral textbook prose.
- Do not add learning objectives, summaries, transitions, examples, proofs, or motivational passages merely because such elements are conventional.
- Do not remove necessary derivations merely to shorten a chapter.
- Do not introduce later mathematical machinery before the chapter in which the user intends to develop it.
- Preserve active source text byte-for-byte during purely structural moves whenever practical, except for `\input` boundaries and final newlines.
- Never mix a structural refactor with an unrequested mathematical rewrite.
- Do not edit inactive alternatives or generated artefacts.

## Information hierarchy

Typography must reveal mathematical hierarchy without turning the page into a collection of coloured panels.

Use the established environments consistently:

- `definitionbox` for definitions and canonical formulas that define an object;
- `theorembox` for theorems, criteria, and reusable mathematical results;
- `examplebox` for worked examples;
- `derivationbox` for calculations deriving a result from earlier conditions;
- `proofbox` for proofs or explicit verifications;
- `interpretationbox` for geometric or conceptual meaning;
- `remarkbox` for cautions, exceptions, and secondary comments;
- `summarybox` only for a genuine synthesis;
- `corebox` only for a central principle that cannot be expressed clearly in ordinary prose.

Definitions and major reusable results may receive visible panels. Narrative, motivation, transitions, explanations, and conclusions should normally remain ordinary prose. Avoid consecutive highlighted blocks. When everything is emphasised, nothing is emphasised.

## Examples, proofs, and diagrams

Examples are not decorative exercises. They must reveal the idea the chapter is trying to communicate.

- Every worked example must be visibly marked as an example.
- A derivation intended for later reuse should end in a clearly marked definition, theorem, or central formula.
- Proofs should be included, omitted, sketched, or deferred according to the chapter intention, not according to a generic standard of completeness.
- Diagrams should explain a construction, obstruction, relation, or change of viewpoint.
- Keep coordinate axes visually distinct from the geometric object being studied.
- Construction stages should be distinguishable when that distinction carries mathematical meaning.
- Keep colours consistent within iterations of the same diagram.
- Avoid labels overlapping paths, points, axes, or one another.
- Do not change global TikZ styles to repair one local figure unless explicitly requested.

## Validation

After a structural or source edit, verify only what is relevant to the requested change:

- every active `\input` target exists;
- no content is included twice;
- removed files are no longer active;
- the edit contains no unrelated prose or mathematical changes;
- the PDF build succeeds when the available repository workflow permits validation.

A successful build does not prove that the lecture expresses the intended mathematics. The user's stated chapter intention remains the final standard.