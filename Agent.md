# Agent Instructions

## Project

- `UnifiedModel_Final.cs.txt` — C# DTOs (`CPV_Modeling.Dtos`): `UnifiedModel` (loan + deposit) and `CommonModelData` (verification items). Keep the existing section-comment layout when adding properties.
- `ruthless-reviewer.md` — code review prompt.
- Remote: https://github.com/Riad133/MyTestGitProj

## Git workflow

- Do day-to-day work on the `dev` branch.
- Merge into `main` only when asked, as a fast-forward (`git merge --ff-only dev`), then push `main` and switch back to `dev`.
- Commit and push only when the user asks.

## Git commits

- Never add a `Co-Authored-By` line (or any other attribution trailer) to git commit messages.
- Use the commit message exactly as given by the user.
