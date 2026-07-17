# AGENTS.md

## Scope

These instructions apply to `mathematical_lectures/mathematical_stories/` and everything below it.

Read this file before working on the lecture.

## Repository workflow

Use the GitHub connector by default for all work with repository files.

Read, edit, create, and delete files through the GitHub connector. Do not invent another repository workflow unless the user explicitly asks for one.

## Source structure

The lecture contains twelve chapters.

The natural source hierarchy is:

```text
chapter directory
  section directory
    subsection files
```

Each chapter has its own directory. Inside the chapter directory, every section has its own directory. Inside each section directory, every subsection is a separate `.tex` file.

Definitions, examples, proofs, derivations, constructions, diagrams, explanations, and formulas belong inside the relevant subsection file. They are content of that subsection, not additional structural levels.

Files should remain small and independently editable, but each file must still represent a coherent subsection.

## Authorial control

The user is the author and lecturer. The user decides what every chapter and section is meant to do.

Before substantial work on a chapter, the user will explain:

- what the chapter is supposed to achieve;
- which ideas should be communicated;
- what the student should understand or notice;
- which examples, observations, theorems, questions, or constructions should drive the chapter;
- what character and rhythm the chapter should have;
- how the chapter should begin and how its mathematical story should develop.

The opening text of a chapter records this intention and is the main instruction for all later work on that chapter.

Do not write or rewrite that opening until the user has explained what the chapter is supposed to be.

## No independent textbook design

Do not independently decide the structure, emphasis, order, tone, examples, proofs, motivation, or narrative of a chapter unless the user explicitly asks for that work.

Do not replace the user's intention with a standard textbook presentation, an encyclopaedic survey, a generic curriculum, or a conventional list of definitions and theorems.

Do not add material merely because it is mathematically standard or because similar textbooks usually contain it.

Do not make the lecture flat, generic, neutral, or complete for its own sake. Every part of the lecture must follow the mathematical intention given by the user.

## Strict work scope

When working on a chapter, section, subsection, diagram, proof, example, definition, or any other specific element, change only that element and only the file that contains it.

Do not modify neighbouring files, related sections, surrounding prose, formatting elsewhere, or any other part of the lecture unless the user explicitly names those additional files or elements.

The small-file structure exists precisely to keep work focused, efficient, and reviewable. Use it to isolate every change.

If a task concerns several concepts, sections, subsections, or files, do not change them all at once. Work interactively, one file at a time. Finish the currently selected file or element, report what was changed, and then continue to the next file only after the user directs the next step.

Do not broaden the scope because another change appears useful, related, necessary for stylistic consistency, or mathematically natural. Ask or wait for explicit instruction.

## Editing rule

Do exactly what the user requests and nothing more.

Do not silently rewrite neighbouring material, reorganise unrelated files, add new rules, preserve old rules, or import conventions from earlier versions unless the user explicitly asks for them.
