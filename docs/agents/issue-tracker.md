# Issue tracker: GitHub & Local Markdown

Issues and specs for this repo live as GitHub issues (`MarioDaeda/lbc-la-buona-community`), with fallback to local markdown files in `.scratch/`.

## GitHub Conventions (Primary)

Use the `gh` CLI for all remote operations:

- **Create an issue**: `gh issue create --title "..." --body "..."`
- **Read an issue**: `gh issue view <number> --comments`
- **List issues**: `gh issue list --state open`
- **Comment**: `gh issue comment <number> --body "..."`
- **Close**: `gh issue close <number> --comment "..."`

## Local Markdown Conventions (Fallback / Solo Planning)

If working offline or for internal draft specs:
- Directories: `.scratch/<feature-slug>/`
- The spec is `.scratch/<feature-slug>/spec.md`
- Implementation tickets: `.scratch/<feature-slug>/issues/<NN>-<slug>.md`

## When a skill says "publish to the issue tracker"

Create a GitHub issue (or write to `.scratch/` if offline).

## When a skill says "fetch the relevant ticket"

Run `gh issue view <number> --comments` or read `.scratch/<effort>/issues/<ticket>.md`.
