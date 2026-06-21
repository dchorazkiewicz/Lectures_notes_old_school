# Effective AI-Assisted Work with Mathematical Documents

This repository can be used as a workspace for lecture notes, problem sets, worked solutions, and polished mathematical documents. An AI assistant can read selected files, discuss the mathematics, create new source files, improve explanations, and prepare a complete document structure.

The most effective model is usually **text first, generated output second**.

## Text files are easy to manage

Plain-text formats such as Markdown, LaTeX, Python, YAML, JSON, shell scripts, and ordinary text files are easy for AI tools and GitHub to handle. They can be read directly, edited precisely, reviewed line by line, compared in Git diffs, merged, corrected, and committed through text-oriented repository APIs.

For mathematical documents, LaTeX is especially useful. It keeps the source readable and editable while supporting professional equations, theorem environments, references, tables, and TikZ graphics.

## Binary files are less convenient

Files such as PDF, PNG, JPG, ZIP, and DOCX can be stored in Git, but they are harder to review, merge, and modify. A small visual change usually produces a completely new binary file, and many repository connectors accept only UTF-8 text rather than arbitrary binary data.

An AI assistant may be able to generate a PDF in its own execution environment, but the connector available in a particular session may not support uploading that PDF directly. Direct binary commits should therefore not be treated as the default workflow.

## Recommended workflow

```text
AI or human edits text sources
        ↓
Git commit stores LaTeX, Markdown, scripts, and configuration
        ↓
GitHub Actions compiles the document
        ↓
PDF is published as an artifact, release asset, or committed output
```

The editable source remains the primary version of the document. The PDF is a generated presentation of that source.

This approach keeps mathematical changes visible in Git history, makes builds reproducible, and avoids transferring binary files through text-only connectors. Compilation errors can also be inspected in GitHub Actions logs.

## Example: worked problem solutions

A user can point an AI assistant to a lecture chapter and a problem-set file. The assistant can then create a separate modular solution project without changing the original exercises.

```text
mathematical_lectures/basic_mathematics/
├── chapters/problem_sets/
│   └── algebra_problem_sets.tex
└── solutions/
    └── problem_set_01_matrices/
        ├── main.tex
        ├── preamble.tex
        ├── macros.tex
        ├── solutions/
        │   ├── problem_01.tex
        │   ├── problem_02.tex
        │   └── ...
        └── figures/
```

The assistant can read the relevant theory, solve the exercises, explain every important step, add checks and diagrams, keep each solution in a separate file, and commit the complete LaTeX source. A GitHub Actions workflow can then compile and publish the PDF automatically.

A polished solution document can contain complete derivations, method selection, assumptions, domain restrictions, verification, remarks about common errors, TikZ diagrams, consistent notation, cross-references, and a professional page layout.

## Possible outputs

The same text-first workflow can produce:

- Markdown explanations for quick review;
- modular LaTeX notes;
- student solution PDFs;
- Beamer presentations;
- temporary workflow artifacts;
- stable release assets.

## Example instruction for an AI agent

```text
Read the indicated lecture chapter and problem-set file.
Create a separate modular LaTeX project containing complete solutions.
Commit the editable text sources to the repository.
Use the repository build system or GitHub Actions to compile and publish the PDF.
Do not modify the original problem set.
```

## Practical principle

```text
Store knowledge and structure as text.
Generate polished binary documents from that text.
```

This model allows AI assistants, human authors, Git, and GitHub Actions to work together efficiently while keeping mathematical content reviewable, reproducible, and easy to improve.
