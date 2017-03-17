# DLx Developers
[Return to the DLx website](https://digitallinguistics.io/)

Welcome to the DLx Developers page. Here you can find documentation on DLx tools, assets, and utilities for your various DLx projects. Check out the links below for more, or head to the [Digital Linguistics GitHub page](https://github.com/digitallinguistics) to view all the DLx repositories.

## [DLx Data Format][8]
The official specification for the DLx JSON data format.

## Software
DLx makes the following software packages available. Click the name of the library to see its documentation.

Library       | Description
------------- | -----------
[`dlx‑js`][1] | A JavaScript library for working with linguistic data in DLx format, containing models and views for various kinds of linguistic objects

## API
A REST API for developers to store, retrieve, and search data in the online DLx database. Register your application [here][10] or at the link below to start interacting with the API.

* [Application Registration Portal][10]
* [Authenticating with the API][11]
* [How to Use the API][7]
* [API Reference][12]

## Databases
DLx provides the following libraries that make it easy for developers to persist DLx data to a local or server-side database.

Library             | Description
------------------- | -----------
[`dlx‑idb`][2]      | A JavaScript library for storing DLx data client-side in [IndexedDB][3]
[`dlx‑api‑js`][4]   | A client-side JavaScript library for interacting with the DLx REST API
[`dlx‑api‑node`][5] | A server-side JavaScript (Node.js) library for interacting with the DLx REST API
[`dlx-db`][6]       | A client-side JavaScript library that connects to both IndexedDB and the DLx REST API, allowing users to sync data between both (essentially a wrapper for `dlx-idb` and `dlx-api-js`)

## [Styles][9]
A repository containing images and branding assets, code style guides, and LESS / CSS style guides for the DLx website and tools.

[1]:  http://developer.digitallinguistics.io/dlx-js
[2]:  http://developer.digitallinguistics.io/dlx-idb
[3]:  https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API
[4]:  http://developer.digitallinguistics.io/dlx-api-js
[5]:  http://developer.digitallinguistics.io/dlx-api-node
[6]:  http://developer.digitallinguistics.io/dlx-db
[7]:  http://developer.digitallinguistics.io/api
[8]:  http://developer.digitallinguistics.io/spec
[9]:  http://developer.digitallinguistics.io/styles
[10]: https://myapps.digitallinguistics.io
[11]: http://developer.digitallinguistics.io/api#authentication
[12]: https://app.swaggerhub.com/api/DLx/dlx/
