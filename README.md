<h1 align="center">
    React Template
</h1>

<div align="center">

[![](https://img.shields.io/badge/yarn-v1.22.5-blue?style=flat-square)](https://yarnpkg.com/)
[![](https://img.shields.io/badge/webpack-v5.35.1-blue?style=flat-square)](https://webpack.js.org/blog/2020-10-10-webpack-5-release/)
[![](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://github.com/Tushar1998/react-typescript-template/pulls)
[![](https://img.shields.io/badge/styled--components-v5.2.3-orange?style=flat-square)](https://styled-components.com/)
[![](https://img.shields.io/badge/%3C%2F%3E-TypeScript-blue?style=flat-square)](https://www.typescriptlang.org/)
[![](https://img.shields.io/badge/node-latest-green?style=flat-square)](https://nodejs.org)

</div>

# Description

This Template is for building React efficient React Frontend Apps. It uses modern JavaScript, is built with [TypeScript](https://www.typescriptlang.org/) (typed superset of JavaScript that compiles to plain JavaScript) and several addons for efficient development

# Specification

- Package Manager : ๐งถ yarn Version 1.22.5
- Compiler : ๐ค Babel Version 7
- Framework : ๐ฅ React Project (TypeScript) Version 17
- Bundler : ๐ฆ Webpack Version 5
- Styling : ๐ styled-components (supports traditional css/scss)
- Component Preview : ๐ Storybook with Webpack 5 bundler
- Development : ๐จ eslint, prettier, editorconfig
- Testing : ๐งช React Testing Library with Jest
- Environment Variable -
     - APP_ENV - Current build / running environment. Default is local.
- Environment Configuration - โ๏ธ Support with deployment specific environment files
     - .env.example - Define a schema of what variables should be defined in .env.{your_APP_ENV}. It throws an error if all values are not configured
     - Access the env variable in javascript using process.env.&lt;your-env-variable&gt;
- Code Spiltting : ๐ Webpack Split Chunks (basic)
- Tree Shaking : ๐ฒ Webpack Terser Plugin (basic)
- Clone Branch react-router if you want to use [react-router-dom](https://reactrouter.com/)
