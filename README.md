# .github

Default issue forms and pull request template for Cellar-Mander repositories.

GitHub uses these in any repository of this account that has no files of its own:

- `.github/ISSUE_TEMPLATE/`: used only when the repository has **no** `.github/ISSUE_TEMPLATE/` folder at all. A single file there hides every form here. The forms must stay in this folder: GitHub ignores a top-level `ISSUE_TEMPLATE/` for shared issue forms.
- `pull_request_template.md`: used when the repository has no PR template of its own.

`.github/ISSUE_TEMPLATE/config.yml` turns off blank issues for people without write access. Owners and maintainers still see a "Blank issue" option, marked as maintainers only.

Keep the forms free of plugin names, so they fit every repository.
