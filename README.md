# .github

Organization-wide default community health files for **Lightnet-Group**.

## Issue templates

The issue forms in [`.github/ISSUE_TEMPLATE`](.github/ISSUE_TEMPLATE) are used by every repository in the organization that has no `.github/ISSUE_TEMPLATE` folder of its own:

| Template | Label | Purpose |
| --- | --- | --- |
| Bug report | `bug` | Something is broken or not working as expected |
| Feature request | `enhancement` | A new feature or an improvement |
| Task / chore | `task` | Internal work, such as maintenance, refactoring or tooling |

Blank issues are disabled (see [`config.yml`](.github/ISSUE_TEMPLATE/config.yml)).

### Overriding per repository

To use different templates in a repository, add its own `.github/ISSUE_TEMPLATE` folder. GitHub then ignores the organization defaults for that repository entirely; individual templates are not merged.

### Notes

- This repository must be **public**, and the templates must be on the **default branch**, for the defaults to apply.
- Issues opened from a form are added to the org project [#9](https://github.com/orgs/Lightnet-Group/projects/9) automatically. This requires the author to have write access to the project; otherwise the issue is still created, just not added.
- If a label such as `task` does not exist in a repository, GitHub skips it when the issue is created.
