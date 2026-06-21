# AI-Assisted Problem Solving and PDF Solution Notes

This repository can be used not only to store lecture notes and problem sets, but also to create complete, well-formatted solution documents with the help of an AI assistant such as ChatGPT.

## Two practical ways to work

### 1. Interactive work in chat

A user can point the assistant to a specific file in the repository, for example a lecture chapter or a problem-set source file, and ask it to:

- read the relevant theory and exercises,
- solve selected or all problems,
- explain the reasoning step by step,
- check calculations and assumptions,
- prepare polished LaTeX source for the solutions.

This mode is useful for discussion, verification, and gradual development of individual solutions.

### 2. Repository-aware document generation

An AI agent with access to the repository and its own execution environment can perform the complete workflow:

1. read `tree.txt`, `AGENTS.md`, the source chapter, and the selected problem set;
2. create a separate solution structure without modifying the original exercises;
3. write mathematically correct and pedagogically explained LaTeX solutions;
4. compile the document to PDF;
5. inspect the compilation result and correct formatting or LaTeX errors;
6. commit the source files and, when the PDF is an intended repository output, the compiled PDF to GitHub.

A possible structure is:

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
        └── main.pdf
```

The exact location may be adapted to the project, but the original problem files should remain unchanged and the solutions should be kept in a clearly separated, modular structure.

## Expected quality of the solution documents

The generated material should be more than a list of final answers. A good solution PDF should contain:

- complete reasoning and intermediate steps,
- clear identification of the method being used,
- explicit assumptions and domain restrictions,
- verification of results where appropriate,
- consistent mathematical notation,
- real LaTeX typesetting,
- readable theorem, remark, and solution boxes,
- TikZ diagrams when a geometric illustration is useful,
- a clean structure suitable for presentation, revision, or distribution.

Temporary build files such as `.aux`, `.log`, `.out`, and `.toc` should not be committed.

## Example instruction for an AI agent

```text
Read the lecture chapter and the indicated problem-set file in this repository.
Create a separate modular LaTeX project containing complete solutions.
Explain every important step, preserve mathematical rigor, compile the PDF,
review the result, and commit the source files and final PDF to the correct branch.
Do not modify the original problem set.
```

This workflow makes it possible to move directly from repository exercises to complete, professionally formatted mathematical solution notes while keeping the source material, explanations, and final PDF under version control.
