# Contributor Guidelines

:star2: Thank you for contributing to the DLx project! :star2:

Below are some general guidelines and information that apply to any of the DLx projects.

## General Coding Guidelines

* Avoid third-party libraries and frameworks when possible. This helps keep the code lightweight and easy for contributors to understand without needing to learn a new library or framework.

* Code for accessibility. Use semantic markup and ARIA roles, and follow other best practices for accessibility. An excellent introduction to web accessibility is [_Inclusive design patterns: Coding accessibility into web design_][2] by Heydon Pickering.

* Code for a variety of device sizes (mobile, tablet, desktop, etc.), using responsive designs that require as few breakpoints as possible. This helps ensure a good user experience regardless of the device used.

* Code using the latest syntax, but compile your code with [Babel][1], using the `env` preset to target the latest two versions of Chrome, Edge, Firefox, iOS Safari, and desktop Safari. Use polyfills for Web APIs (such as `Fetch`) that are not supported in the latest version of those browsers. This allows you to write your code in a convenient manner, but ensure that it still runs on all modern browsers.

* Document your code using [JSDoc][3], even if you aren't producing live documentation for the code.

* Developer-facing documentation should include [self-documenting code][10], [JSDoc-style comments][6], and documentation of build processes or other important information in [markdown][11] files.

* Consider including `README`, `LICENSE`, `MAINTAINERS`, or other related files in the parts of projects you are the primary owner of.

* DLx has a recommended ESLint stylesheet for JavaScript available [here][5]. If your development environment supports ESLint, you can download the file, include it in the project directory, and automatically have your code linted (checked) while you type. (If you are using Atom as a text editor, install the package `linter-eslint`.)

[1]: https://babeljs.io/
[2]: https://www.amazon.com/Inclusive-Design-Patterns-Heydon-Pickering-ebook/dp/B01MAXK8XR/ref=sr_1_1?ie=UTF8&qid=1498679370&sr=8-1&keywords=inclusive+design
[3]: http://usejsdoc.org/index.html
