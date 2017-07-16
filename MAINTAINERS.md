# Maintainer's Guide
This is a general-purpose guide for maintainers of DLx projects.

## Workflow
Below is the general workflow to use for DLx projects. It is designed to ensure that every change to a project is tracked by a GitHub issue, and, where applicable, a project board.

1. Open new issues

1. Triage issues on the project board

1. Create a new milestone

1. Choose issues from project board to include in milestone

1. Select an issue to work on

1. Create issue branch (e.g. `issue-167`)

1. Bump version number for that project

1. Update docs / readme with information to reflect the changes you'll be making

1. Plan and write / update a test for the change, if applicable

1. Write code so that your tests pass

1. Update inline commenting in code (especially JSDoc comments)

1. Update docs / readme again if your changes deviated from what you wrote earlier

1. Run build process (`npm run build`), potentially including:
  - transpiling JS (`npm run transpile` - often included in the bundle step)
  - bundling modules (`npm run bundle` - often includes transpiling JS)
  - compiling LESS (`npm run less`)
  - compiling Handlebars (`npm run hbs`)
  - creating documentation, typically with JSDoc (`npm run docs`)

1. Add commit message that closes the related issue (e.g. `closes #167`)
1. Commit and push
1. Open a pull request to the milestone branch, if present, or `master` branch otherwise
1. Address any changes requested in the pull request review
1. (Admin / Maintainer) Squash and merge pull request
1. Repeat process with another issue
