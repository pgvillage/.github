# .github

Default community health files for the repositories of the **pgvillage** organization: issue templates and the pull
request template. GitHub uses them in every repository of the organization that doesn't have its own.

## What's here

- `.github/ISSUE_TEMPLATE/`: bug report, feature request, codebase improvement, support question.
- `.github/PULL_REQUEST_TEMPLATE.md`: the pull request template. The type of change is in the title (Conventional
  Commits, checked by `Validate PR Title`), so the template doesn't ask for it.

A repository that has its own `.github/ISSUE_TEMPLATE/` folder or `PULL_REQUEST_TEMPLATE.md` uses those instead, so
repositories should not keep their own copies.

The workflow and `CODEOWNERS` in `.github/` are for this repository only; they are not defaults.
