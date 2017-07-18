# Contributor Guidelines

:star2: Thank you for contributing to DLx! :star2:

Below are some general guidelines and information that apply to any of the DLx projects. Each DLx project also has its own set of contributing guidelines, available in the `CONTRIBUTING.md` file in the root folder of the GitHub repository for that project.

## Join DLx on Slack!
[![Join DLx on Slack!][8]][7]

## About Digital Linguistics

Digital Linguistics (DLx) is the science of the digital management, storage, and dissemination of linguistic data. Best practice in Digital Linguistics is to use the modern open web platform - primarily HTML, CSS, JavaScript, & JSON - for working with linguistic data. DLx projects aim to accommodate the ways linguists already think about and work with their data, and to provide an interoperable data format and set of tools for linguists to use. DLx projects are entirely open source, and aim for simplicity such that other collaborators in the community can contribute to any DLx project.

## Code of Conduct

DLx uses the [Contributor Covenant for open source projects][5] as its code of conduct. You can read the code of conduct [here][5]. Be sure to read this before starting your contribution.

## Requesting Features & Reporting Bugs

DLx projects use GitHub issues and project boards for tracking all bugs, features, and tasks. To request a feature for a project or report a bug, go to the issues page in that project's GitHub repository. A complete list of DLx repositories can be found [here][4].

## Contributor Roles

DLx uses three separate roles for managing project contributors:

1. `maintainer` - Responsible for code review, general direction, and high-level decisions for a project. 2-4 people per project. Maintainers (and admins) are the only people who can push to the `master` branch in a project.

1. `developer` - A person with commit access to DLx repositories. Anyone who makes a contribution to a DLx project and has their pull request merged is automatically added to the DLx Developers team on GitHub, and is given write access to all DLx repositories (pushes to the `master` branch will still be restricted to maintainers and admins).

1. `contributor` - Anyone who contributes to DLx in any way, whether by opening an issue, joining discussion on GitHub or Slack, or publishing / presenting on Digital Linguistics. Anyone is allowed to join the DLx Slack team and the discussions there - just email [dhieber@umail.ucsb.edu](mailto:dhieber@umail.ucsb.edu) for an invite.

## General Coding Guidelines

* Avoid third-party libraries and frameworks when possible. This helps keep the code lightweight and easy for contributors to understand without needing to learn a new library or framework.

* Code for accessibility. Use semantic markup and ARIA roles, and follow other best practices for accessibility. An excellent introduction to web accessibility is [_Inclusive design patterns: Coding accessibility into web design_][2] by Heydon Pickering.

* Code for a variety of device sizes (mobile, tablet, desktop, etc.), using responsive designs that require as few breakpoints as possible. This helps ensure a good user experience regardless of the device used.

* Code using the latest syntax, but compile your code with [Babel][1], using the `env` preset to target the latest two versions of Chrome, Edge, Firefox, iOS Safari, and desktop Safari. Use polyfills for Web APIs (such as `Fetch`) that are not supported in the latest version of those browsers. This allows you to write your code in a convenient manner, but ensure that it still runs on all modern browsers.

* If a CSS property is not supported by the latest versions of Chrome, Edge, Firefox, iOS Safari, and desktop Safari, include an appropriate fallback.

* Document your code using [JSDoc][3], even if you aren't producing live documentation for the code.

* Developer-facing documentation should include [self-documenting code][10], [JSDoc-style comments][6], and documentation of build processes or other important information in [markdown][11] files.

* Consider including `README`, `LICENSE`, `MAINTAINERS`, or other related files in the parts of projects you are the primary owner of.

* DLx has a recommended ESLint stylesheet for JavaScript available [here][5]. If your development environment supports ESLint, you can download the file, include it in the project directory, and automatically have your code linted (checked) while you type. (If you are using Atom as a text editor, install the package `linter-eslint`.)

## Maintainers
Project maintainers should follow the guidelines in the [Maintainer's Guide][6].

[1]: https://babeljs.io/
[2]: https://www.amazon.com/Inclusive-Design-Patterns-Heydon-Pickering-ebook/dp/B01MAXK8XR/ref=sr_1_1?ie=UTF8&qid=1498679370&sr=8-1&keywords=inclusive+design
[3]: http://usejsdoc.org/index.html
[4]: https://github.com/digitallinguistics
[5]: http://contributor-covenant.org/
[6]: https://github.com/digitallinguistics/digitallinguistics.github.io/blob/master/MAINTAINERS.md
[7]: https://slack.digitallinguistics.io/
[8]: https://dlx-slack.azurewebsites.net/badge.svg
