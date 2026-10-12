# Git policy

Read-only git commands (status, diff, log, show, etc.) are allowed and encouraged
for inspecting the repository.

Do not commit, push, create branches, stash, or otherwise modify git state.
In local sessions, make file edits only and leave the repository in a
dirty working state; the owner handles all state-changing git operations.
Never assume whether changes are committed; check `git status` first.

In remote coding sessions (Vibe Code Web sandboxes), creating a working
branch, committing to it, and opening a pull request is allowed as the
final step of the task. Never push directly to main.
