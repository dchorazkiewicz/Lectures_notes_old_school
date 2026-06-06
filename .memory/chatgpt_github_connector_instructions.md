# ChatGPT GitHub Connector Instructions for Damian

These instructions describe how ChatGPT should work with Damian's GitHub
repository through the GitHub connector.

## Default Repository

The default repository is:

```text
dchorazkiewicz/Lectures_notes_old_school
```

The default branch is:

```text
main
```

unless Damian explicitly and unambiguously asks for that repository.

## Required Repository Selection Check

Before doing any GitHub work, make sure that the active repository selected in
the ChatGPT GitHub selector is:

```text
GitHub -> dchorazkiewicz/Lectures_notes_old_school
```

GitHub App permissions alone are not enough. The active repository must also be
selected in the chat's GitHub selector.

The correct connector namespace is:

```text
GitHub/dchorazkiewicz/Lectures_notes_old_school
```

If the active namespace shows:

```text
GitHub/dchorazkiewicz/Mathematics_Physics_Lectures
```

or any other repository, do not write anything. Ask Damian to switch the active
repository in the GitHub selector first.

## Required Initial Reads

Before searching for files, recognizing repository structure, or editing
anything, first read `tree.txt` using a full GitHub URL:

```text
https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/tree.txt
```

The correct repository structure file is:

```text
tree.txt
```

not:

```text
tree.md
```

After reading `tree.txt`, also read `AGENTS.md` using a full GitHub URL:

```text
https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/AGENTS.md
```

`tree.txt` tells ChatGPT what files and folders exist. `AGENTS.md` tells ChatGPT
how to work inside the repository: project structure, LaTeX editing rules,
compilation rules, shared files, figures, problems, and repository workflow.

Recommended order:

1. Confirm the active GitHub repository selector.
2. Read `tree.txt`.
3. Read `AGENTS.md` once at the beginning of the conversation or work session.
4. Search or fetch the specific files needed for the task.
5. Edit only the appropriate files.
6. Verify after writing.

Do not re-read `AGENTS.md` before every small action unless there is a reason to
believe it changed or the work session has shifted to a substantially different
task. The intended pattern is: read `AGENTS.md` at the start of the conversation,
keep its rules in mind, and continue working from that context.

If `AGENTS.md` changes during the conversation, re-read it before continuing
repository work.

Rules in the repository-local `AGENTS.md` override generic assumptions about how
LaTeX repositories should be edited.

## Reading Files

For reading files, always use full GitHub URLs through:

```text
GitHub/dchorazkiewicz/Lectures_notes_old_school.fetch
```

Do not use short paths for reading.

Full URL format:

```text
https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/<path_from_repo_root>
```

Treat paths provided by Damian as relative to the repository root, then build
the full GitHub URL from them.

Example:

```text
https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/shared/styles.tex
```

Do not guess file paths. If a path is uncertain, read `tree.txt` or use repository
search first.

## Searching

Use:

```text
GitHub/dchorazkiewicz/Lectures_notes_old_school.search
```

with:

```text
repository_name="dchorazkiewicz/Lectures_notes_old_school"
topn=10
```

and a focused `query`.

## Creating Files

To create a file, use:

```text
GitHub/dchorazkiewicz/Lectures_notes_old_school.create_file
```

with:

```text
repository_full_name="dchorazkiewicz/Lectures_notes_old_school"
branch="main"
path="<relative_path_from_repo_root>"
content="<complete_file_content>"
message="<commit_message>"
```

For GitHub API write operations, `path` must be relative to the repository root.

## Updating Files

To update an existing file:

1. First fetch the file using its full GitHub URL.
2. If `update_file` requires a SHA, get the SHA with `fetch_file` using the
   correct repository and the path relative to the repository root.
3. Use `update_file` only in the correct namespace:

```text
GitHub/dchorazkiewicz/Lectures_notes_old_school
```

with:

```text
repository_full_name="dchorazkiewicz/Lectures_notes_old_school"
branch="main"
path="<relative_path_from_repo_root>"
content="<complete_replacement_file_content>"
message="<commit_message>"
sha="<current_file_sha>"
```

4. After the commit, verify by fetching the file again using its full GitHub URL.

Important distinction:

- GitHub API write operations require relative paths in `path`.
- Reading and verification should always use full GitHub URLs.

## Verification After Writes

After every write, check that the commit and file are in:

```text
dchorazkiewicz/Lectures_notes_old_school
```

If a commit appears in:

```text
dchorazkiewicz/Mathematics_Physics_Lectures
```

or any other repository, stop immediately and ask Damian to switch the active
repository in the GitHub selector.

After write operations, verify that any returned commit URL, file URL, or
repository name belongs to:

```text
dchorazkiewicz/Lectures_notes_old_school
```

Do not edit generated PDFs or LaTeX build artifacts directly. Edit source files
and rebuild when needed.

If a write changes the repository structure, expect `tree.txt` to be updated by
GitHub Actions. Before the next separate write task, re-read `tree.txt` from
GitHub so the connector has the current structure.

## Correct Read Test

A correct read test is:

```text
fetch https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/tree.txt
```

Expected result:

ChatGPT reads `tree.txt` from:

```text
dchorazkiewicz/Lectures_notes_old_school
```

## Correct Write Test

A correct write test is:

```text
create_file
repository_full_name="dchorazkiewicz/Lectures_notes_old_school"
branch="main"
path="connector_write_read_test.md"
content="Connector read/write test for dchorazkiewicz/Lectures_notes_old_school."
message="Test connector write access"
```

After the write test, verify the file by fetching:

```text
https://github.com/dchorazkiewicz/Lectures_notes_old_school/blob/main/connector_write_read_test.md
```

## Core Safety Rule

Never write to GitHub unless the active repository selector and connector
namespace both point to:

```text
dchorazkiewicz/Lectures_notes_old_school
```

When in doubt, stop and ask Damian to confirm the active repository.
