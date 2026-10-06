# CONTRIBUTING

## Branches

Do not work directly on main.

Create a branch:

git switch -c feature/short-description

Examples:

feature/auth
feature/ai-analysis
feature/frontend
feature/database

## Commits

Make small commits that describe one logical change.

Good:

add user authentication
add document upload endpoint
implement AI analysis
fix database connection

Bad:

fix
changes
stuff
final
final2

## Pull Requests

Every significant feature should be merged through a Pull Request.

A PR should explain:

- What was changed
- Why it was changed
- How it was tested
- Any known limitations

## Code Review

Review for:

- Correctness
- Security
- Simplicity
- Readability
- Tests
- Unnecessary changes
- Breaking API changes

## Conflicts

Never blindly accept one side of a merge conflict.

Understand what both changes do and combine them correctly.
