# PWA Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![NPM-Package: Express@4.17.1](https://img.shields.io/badge/NPM_Package-Express@4.17.1-blue.svg)](https://www.npmjs.com/package/express)
[![NPM-Package: concurrently@5.2.0](https://img.shields.io/badge/NPM_Package-concurrently@5.2.0-green.svg)](https://www.npmjs.com/package/concurrently)
[![NPM-Package: webpack@5.51.1](https://img.shields.io/badge/NPM_Package-webpack@5.51.1-teal.svg)](https://www.npmjs.com/package/webpack)
[![NPM-Package: @babel/core@7.15.0](https://img.shields.io/badge/NPM_Package-@babel%2Fcore@7.15.0-brown.svg)](https://www.npmjs.com/package/@babel/core)

## Description

This project presents an innovative text editor web application designed with developers in mind. Beyond mere text editing, it facilitates the creation and retrieval of notes or code snippets, ensuring reliable access even without an active internet connection. Leveraging Webpack, the application guarantees optimized bundling of its JavaScript assets, supplemented with plugins to automatically produce key assets like an HTML file, a service worker, and a manifest.

Despite the usage of next-gen JavaScript, the application ensures error-free operations across all browsers. Upon user engagement, the editor instantiates an IndexedDB database, capturing all entered content. This mechanism ensures that any saved notes are instantly retrievable upon relaunching the editor. For added convenience, users can install the web application directly onto their desktop, benefiting from a registered service worker that efficiently serves cached assets for rapid load times and offline readiness.

## Table of Contents

- [Getting Started](#getting-started)
  - [Cloning the Repository](#cloning-the-repository)
  - [Install Dependencies](#install-dependencies)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)
- [Acknowledgements](#acknowledgements)
- [Questions](#questions)

## Getting Started

### Cloning the Repository

To clone the repository, navigate to the directory you want to clone the repository into.

Then, run the following command.

```bash
git clone 'git@github.com:Verouge/README-Generator.git'
```

### Install Dependencies

To install dependencies, run the following command:

```bash
npm i
```

## Usage

### Local Development

To start the application, run the following command:

```bash
npm run start
```

### Production Build

This application is deployed to heroku.
https://pwa-jate-te-eebcfa312069.herokuapp.com/

![](/assets/images/demo.png)

## Contributing

Please contact me to add your contributions

## License

This project is licensed under the MIT license.

```
Copyright <2023> <Brandon Zhang>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## Credits

Brandon Zhang

## Acknowledgements

This project utilizes a variety of tools and libraries to achieve its functionality:

- **Express**: A swift, minimalist, and adaptable Node.js web application framework. It equips the app with a strong set of features for both web and mobile applications. [Official website](https://expressjs.com/)

- **if-env**: An npm package that helps in managing scripts based on the current NODE_ENV or another environment variable. This ensures that the right scripts run in the appropriate environments, streamlining the development and deployment process. [View on npm](https://www.npmjs.com/package/if-env)

- **concurrently**: Allows executing multiple npm scripts concurrently. It's especially useful during development when you might want to run a backend server and a frontend dev server at the same time. [View on npm](https://www.npmjs.com/package/concurrently)

- **nodemon**: A utility that monitors any changes in your source and automatically restarts your server, making the development process smoother. [View on npm](https://www.npmjs.com/package/nodemon)

- **Babel**: A powerful JavaScript transpiler that converts ES6+ code into a backwards-compatible version for older browsers and environments. Several Babel plugins and presets are also used in this project to ensure optimal compatibility and performance. [Official website](https://babeljs.io/)

- **webpack**: A module bundler and task runner that boosts the project's efficiency by bundling different assets like scripts, images, and styles. [Official website](https://webpack.js.org/)

- **css-loader**, **style-loader**: Essential loaders for processing and bundling CSS files in the webpack.

- **html-webpack-plugin**: Simplifies the creation of HTML files to serve the webpack bundles. [View on npm](https://www.npmjs.com/package/html-webpack-plugin)

- **http-server**: A simple zero-configuration command-line HTTP server. It's powerful enough for production usage but it's simple and hackable enough for testing, local development, and learning. [View on npm](https://www.npmjs.com/package/http-server)

- **code-mirror-themes**: A package that provides a variety of themes for CodeMirror, an in-browser text editor known for features like syntax highlighting and code folding. [View on npm](https://www.npmjs.com/package/code-mirror-themes)

- **idb**: A tiny library that mirrors indexedDB, but with promises. It provides an efficient method of client-side storage. [View on npm](https://www.npmjs.com/package/idb)

- **webpack-pwa-manifest**: A plugin for generating a manifest for your Progressive Web Application, aiding in the creation of Web App Manifests and supporting the app's PWA needs. [View on npm](https://www.npmjs.com/package/webpack-pwa-manifest)

- **workbox-webpack-plugin**: A library that generates a service worker for your app and integrates with the webpack build process, making it easier to ensure that your web app works offline. [View on npm](https://www.npmjs.com/package/workbox-webpack-plugin)

## Questions

If you have any questions, please feel free to contact me via email or on GitHub.

Email: branola1998628@gmail.com

GitHub: [Verouge](https://github.com/Verouge)
