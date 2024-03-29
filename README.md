# DLx Developers

Welcome to the DLx Developers page! Here you can find documentation on DLx tools, assets, and utilities for your various DLx projects. Check out the links below for more, or head to the [Digital Linguistics GitHub page][GitHub] to view all the DLx repositories.

## Contents

<!-- TOC -->

- [About Digital Linguistics](#about-digital-linguistics)
- [DLx on the Web](#dlx-on-the-web)
- [Web Apps & Tools](#web-apps--tools)
- [Data Formats](#data-formats)
- [JavaScript Libraries](#javascript-libraries)
- [Converters](#converters)
- [Developer Resources](#developer-resources)

<!-- /TOC -->

## About Digital Linguistics

Digital Linguistics (DLx) is the science of the digital management, storage, and dissemination of linguistic data. Best practice in Digital Linguistics is to use the modern open web platform—primarily HTML, CSS, JavaScript, & JSON—for working with linguistic data. DLx projects aim to accommodate the ways linguists already think about and work with their data, and to provide an interoperable data format and set of tools for linguists to use. DLx projects are entirely open source, and aim for simplicity such that other collaborators in the community can contribute to any DLx project.

## DLx on the Web

- [Blog][Blog]
- [GitHub][GitHub]
- [Website][Website]

## Web Apps & Tools

- ### [Oxalis][Oxalis]

    The DLx portal for viewing, searching, and aggregating data across multiple languages and projects. The goal of Oxalis is to enable data access for both researchers and speakers, as well as large-scale, data-intensive projects, especially those in typology.

- ### [Lotus (Web App for Managing Linguistic Data)][Lotus]

    A web app for linguists to enter, edit, and manage their linguistic data and corpora. Includes tools for managing lexicons and texts, and for tagging corpora. Works offline or online, and allows for online collaboration.

- ### [Tulip (Tools for Linguistic Productivity)][Tulip]

    A collection of standalone tools and utilities for accomplishing specific tasks when working with language data, such as converting between different text formats or writing systems.

## Data Formats

- ### [DaFoDiL (Data Format for Digital Linguistics)][DaFoDiL]

    Guidelines for representing linguistic data in JSON.

- ### [Scription][Scription]

    Scription is a simple plain-text format for representing linguistic texts that is computer-readable.

## JavaScript Libraries

- ### [Concordance Library][Concordance]

    _(Node)_ A library for creating a concordance of words in a DLx-formatted corpus.

- ### [Transliteration Library][Transliterate]

    _(browser, Node)_ A library for transliterating text from one writing system to another. May also be used to sanitize text by removing unwanted characters.

- ### [Word Aligner Library][Word-Aligner]

    _(browser, Node)_ A library for vertically aligning interlinear glosses (or any multi-line format), using tabs or white space.

## Converters

The following JavaScript libraries convert data between various formats. Each converter is also available as a tool in [Tulip][Tulip].

- [Scription > DLx](scription2dlx)
- [Tagged Text > DLx](tags2dlx)

## Developer Resources

DLx makes the following developer resources available:

- [CSS Pattern / Style Library][Styles]
- [CSS Stylesheet][Stylelint] (Stylelint)
- [JavaScript Stylesheet][ESLint] (ESLint)

<!-- Links -->
[Blog]:          https://medium.com/digital-linguistics
[Concordance]:   https://developer.digitallinguistics.io/concordance
[DaFoDiL]:       https://format.digitallinguistics.io
[ESLint]:        https://github.com/digitallinguistics/digitallinguistics.github.io/blob/master/stylesheets/.eslintrc.yml
[GitHub]:        https://github.com/digitallinguistics/
[Lotus]:         https://developer.digitallinguistics.io/app
[Oxalis]:        https://developer.digitallinguistics.io/data-explorer
[Scription]:     https://scription.digitallinguistics.io
[scription2dlx]: https://developer.digitallinguistics.io/scription2dlx/
[Stylelint]:     https://github.com/digitallinguistics/digitallinguistics.github.io/blob/master/stylesheets/.stylelintrc.yml
[Styles]:        https://styles.digitallinguistics.io
[Transliterate]: https://developer.digitallinguistics.io/transliterate
[tags2dlx]:      https://developer.digitallinguistics.io/tags2dlx/
[Tulip]:         https://github.com/digitallinguistics/tools/blob/master/.github/CONTRIBUTING.md
[Website]:       https://digitallinguistics.io/
[Word-Aligner]:  https://developer.digitallinguistics.io/word-aligner/
