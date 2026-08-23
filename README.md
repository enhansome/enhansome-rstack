# Awesome rstack with stars

<p align="center">
    <img width="300" src="./logo.png" alt="logo of rspack-awesome repository"><br>
    A curated list of awesome things related to the Rstack toolchain
</p>

<h1>Awesome Rstack</h1>

* [Resources](#resources)
  * [Rstack](#rstack)
  * [Official Resources](#official-resources)
  * [Ecosystem](#ecosystem)
* [Starter](#starter)
  * [Rspack Starter](#rspack-starter)
  * [Rsbuild Starter](#rsbuild-starter)
  * [Rslib Starter](#rslib-starter)
* [Plugins](#plugins)
  * [Rspack Plugins](#rspack-plugins)
  * [Rspack Loaders](#rspack-loaders)
  * [Rsbuild Plugins](#rsbuild-plugins)
  * [Rspress Plugins](#rspress-plugins)
  * [Unplugin](#unplugin)
* [Rstest Adapters](#rstest-adapters)
* [Deployment](#deployment)
* [Libraries](#libraries)
* [Blogs](#blogs)
* [License](#license)

## Resources

### Rstack

Rstack is a unified JavaScript toolchain built around Rspack, with high performance and consistent architecture.

| Name                                                                                                     | Description              | Version                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------- | ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Rspack](https://github.com/web-infra-dev/rspack) ⭐ 12,868 \| 🐛 272 \| 🌐 Rust \| 📅 2026-08-23         | Bundler                  | <a href="https://npmjs.com/package/@rspack/core"><img src="https://img.shields.io/npm/v/@rspack/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rsbuild](https://github.com/web-infra-dev/rsbuild) ⭐ 3,363 \| 🐛 23 \| 🌐 TypeScript \| 📅 2026-08-23   | Build tool               | <a href="https://npmjs.com/package/@rsbuild/core"><img src="https://img.shields.io/npm/v/@rsbuild/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rslib](https://github.com/web-infra-dev/rslib) ⭐ 1,002 \| 🐛 28 \| 🌐 TypeScript \| 📅 2026-08-22       | Library development tool | <a href="https://npmjs.com/package/@rslib/core"><img src="https://img.shields.io/npm/v/@rslib/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>       |
| [Rspress](https://github.com/web-infra-dev/rspress) ⭐ 2,313 \| 🐛 57 \| 🌐 TypeScript \| 📅 2026-08-21   | Static site generator    | <a href="https://npmjs.com/package/@rspress/core"><img src="https://img.shields.io/npm/v/@rspress/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rsdoctor](https://github.com/web-infra-dev/rsdoctor) ⭐ 1,140 \| 🐛 26 \| 🌐 TypeScript \| 📅 2026-08-22 | Build analyzer           | <a href="https://npmjs.com/package/@rsdoctor/core"><img src="https://img.shields.io/npm/v/@rsdoctor/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a> |
| [Rstest](https://github.com/web-infra-dev/rstest) ⭐ 481 \| 🐛 50 \| 🌐 TypeScript \| 📅 2026-08-21       | Testing framework        | <a href="https://npmjs.com/package/@rstest/core"><img src="https://img.shields.io/npm/v/@rstest/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rslint](https://github.com/web-infra-dev/rslint) ⭐ 446 \| 🐛 80 \| 🌐 Go \| 📅 2026-08-23               | Linter                   | <a href="https://npmjs.com/package/@rslint/core"><img src="https://img.shields.io/npm/v/@rslint/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |

### Official Resources

* [rstack-examples](https://github.com/rstackjs/rstack-examples) ⭐ 166 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-21: Examples for Rstack.
* [rstack-design-resources](https://github.com/rstackjs/rstack-design-resources) ⭐ 17 | 🐛 2 | 📅 2026-08-18: Design resources for Rstack.

### Ecosystem

Upper-level frameworks or libraries that are powered by Rspack or connected to Rspack:

* [Meteor](https://github.com/meteor/meteor) ⭐ 44,810 | 🐛 413 | 🌐 JavaScript | 📅 2026-08-22: An ultra-simple environment for building modern web applications with Rspack.
* [Extension.js](https://github.com/extension-js/extension.js) ⭐ 5,066 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-22: Create, develop, build, and preview browser extensions for Chrome, Firefox, and Edge with Rspack.
* [Re.Pack](https://github.com/callstack/repack) ⭐ 1,931 | 🐛 24 | 🌐 TypeScript | 📅 2026-08-22: A toolkit to build your React Native application with Rspack.
* [xmcp](https://github.com/basementstudio/xmcp) ⭐ 1,317 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-22: A framework for building and shipping MCP servers with TypeScript and Rspack.
* [Esmx](https://github.com/esmnext/esmx) ⭐ 677 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-13: Esmx is a next-generation micro-frontend framework based on native ESM, with no sandbox or runtime overhead, supporting multi-framework hybrid development and providing high-performance server-side rendering capabilities.
* [The Boring JavaScript Stack](https://github.com/sailscastshq/boring-stack) ⭐ 502 | 🐛 3 | 🌐 JavaScript | 📅 2026-06-16: An opinionated full-stack JavaScript starter built with Sails.js, Inertia.js, and Rsbuild-powered frontend assets.
* [Shakapacker](https://github.com/shakacode/shakapacker) ⭐ 490 | 🐛 24 | 🌐 Ruby | 📅 2026-08-23: Make it easy to use the JavaScript pre-processor and Rspack to manage frontend JavaScript in Rails.
* [storybook-rsbuild](https://github.com/rstackjs/storybook-rsbuild) ⭐ 155 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-18: Storybook builder powered by Rsbuild.
* [Addfox](https://github.com/addfox/addfox) ⭐ 121 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03: A browser extension framework built on Rsbuild.
* [Kmi](https://github.com/kmijs/kmi) ⭐ 110 | 🐛 11 | 🌐 JavaScript | 📅 2026-05-15: Based on Umi to provide Rspack support and other best practices.
* [pareto](https://github.com/childrentime/pareto) ⭐ 71 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-06: A lightweight SSR framework centered on stream rendering.
* [Rshono](https://github.com/rshono/rshono) ⭐ 68 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-22: Minimalist web framework based on Hono, Rspack and React Server Components.
* [electron-rsbuild](https://github.com/electron-rsbuild/electron-rsbuild) ⭐ 38 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-27: The Rsbuild-based electron build tool.
* [PrevelteKit](https://github.com/tbocek/preveltekit) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2026-04-16: A lightweight, high-performance web application framework built on Svelte 5, featuring Server-Side Pre Rendering (SSPR) using Rsbuild as the build tool.
* [serverless-rspack](https://github.com/kitchenshelf/serverless-rspack) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-20: A Serverless framework plugin for zero-config JavaScript and TypeScript code bundling using the high performance Rust-based JavaScript bundler rspack.
* [AUmi](https://github.com/atom-yang/aumi) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-29: Use Rsbuild as Umi's bundler instead of Webpack, get high performance of Rsbuild and all Umi ecosystem.
* [Rselectron](https://github.com/guangzan/rselectron) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-12: An Rsbuild-first Electron development and build tool.
* [Rspeedy](https://lynxjs.org/rspeedy/): The Rspack-based build tool designed specifically for [Lynx](https://lynxjs.org/) applications.
* [Modern.js](https://modernjs.dev/): A progressive React framework for web development.
* [@nx/rspack](https://nx.dev/nx-api/rspack): The Nx plugin for Rspack.
* [@nx/rsbuild](https://nx.dev/nx-api/rsbuild): The Nx plugin for Rsbuild.
* [Docusaurus](https://docusaurus.io/blog/releases/3.6#docusaurus-faster): Help you ship a beautiful documentation site in no time.
* [TanStack Start](https://tanstack.com/start/latest): Full-stack Framework powered by TanStack Router for React and Solid.
* [next-rspack](https://rspack.rs/guide/tech/next): Use Rspack as the bundler for Next.js.
* [Nuxt](https://nuxt.com/): An intuitive Vue framework for creating web applications and websites with Vue.js. Install [@nuxt/rspack-builder](https://www.npmjs.com/package/@nuxt/rspack-builder) to use Rspack as the bundler for Nuxt.
* [EMP 3.0](https://empjs.dev/): A high-performance enterprise-level front-end build system built on the Rust ecosystem.
* [cypress-rspack-dev-server](https://www.npmjs.com/package/cypress-rspack-dev-server): Cypress Component-testing with Rust-based web bundler Rspack's dev server.
* [Angular Rspack](https://www.npmjs.com/package/@nx/angular-rspack): Rspack plugin, Rsbuild plugin and tooling for Angular applications.

## Skills

* [agent-skills](https://github.com/rstackjs/agent-skills) ⭐ 88 | 🐛 8 | 🌐 JavaScript | 📅 2026-08-21: A collection of Agent Skills for Rstack.

## Starter

### Rspack Starter

* [vue-admin-better](https://github.com/zxwk1998/vue-admin-better) ⭐ 18,901 | 🐛 18 | 🌐 Vue | 📅 2026-08-23: A Vue 3 admin based on Rspack.
* [ng-rspack](https://github.com/edbzn/ng-rspack) ⭐ 36 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-10: Angular + Rspack + Nx + Module Federation 2.0.
* [electron-react-rspack](https://github.com/RyanProMax/electron-react-rspack) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-31: An Electron boilerplate including TypeScript, React, Rspack and ESLint.
* [nuxt-rspack-starter](https://github.com/danielroe/nuxt-rspack-starter) ⭐ 17 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-22: Nuxt starter with Rspack.
* [shark](https://github.com/h7ml/shark) ⭐ 13 | 🐛 8 | 🌐 TypeScript | 📅 2026-02-12: A React project with Rspack, Ant Design, Ant Design Pro Components, Antd\@5 React\@18 AntV G2Plot, ahooks, react-use, Axios, i18next, localforage, Mock.js, NProgress, and more.
* [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-03
* [r2h](https://github.com/bdxygy/r2h) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-22: A blazing-fast SSR starter powered by React 19, Rspack, and Hono.
* [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-01
* [electron-react-rspack-boilerplate](https://github.com/Sovea/electron-react-rspack-boilerplate) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11: A modern, unopinionated, pure boilerplate for developing electron app with Rspack, React, TypeScript.
* [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2023-11-23

### Rsbuild Starter

* [rsbuild-plugin-template](https://github.com/rstackjs/rsbuild-plugin-template) ⭐ 29 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-20: Use this template to create your own Rsbuild plugin.
* [ding-dong](https://github.com/src-thk/ding-dong) ⭐ 18 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-21: A lightning-fast, modern React template supercharged with Rsbuild.
* [rsbuild-chrome-extension-boilerplate-react](https://github.com/filc-dev/rsbuild-chrome-extension-boilerplate-react) ⚠️ Archived: Chrome extension boilerplate for Rsbuild.
* [react-antd-admin-pro](https://github.com/cl1107/react-antd-admin-pro) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2025-01-14: An admin project template for React. It's built with Rsbuild, React 18, TypeScript 5, antd 5, and React Router.
* [react-tailwind-rsbuild-boilerplate](https://github.com/alonronin/react-tailwind-rsbuild-boilerplate) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-25: React + React Router + Tailwind CSS with Rsbuild boilerplate.
* [TanStacked](https://github.com/mohmmedraad/TanStacked) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27: React + Tanstack Router + Shadcn + Tailwind CSS v4 And Biome with Rsbuild boilerplate.
* [rsbuild\_vue3\_h5\_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2024-03-08: A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.
* [rsbuild-turborepo-react-module-federation](https://github.com/nguyenbatranvan/rspack-turbo-module-federation) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-19: Rsbuild + Turborepo + Biome + Zustand + React for module federation.
* [template-rsbuild-react-ts-tailwind](https://github.com/RoyRao2333/template-rsbuild-react-ts-tailwind) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-21: Rsbuild starter template with React + Typescript + TailwindCSS + Biome.
* [@trapar-waves/react-antd-pro](https://github.com/Trapar-waves/react-antd-pro) ⭐ 4 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-22: A React-based project leveraging Ant Design Pro, TanStack tools, and Rsbuild.
* [@trapar-waves/react-tanstack](https://github.com/Trapar-waves/react-tanstack) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-16: A React template leveraging TanStack tools, with TypeScript, Tailwind CSS, and Rsbuild integration.
* [umi-rsbuild](https://github.com/atom-yang/aumi-example) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-13: `Umi` + `Rsbuild`, A `Umi` project integrated with `Rsbuild`, you can use `Umi` and its plugins with the same experiences as `Umi` + `Webpack` are.
* [@trapar-waves/vue-tailwind](https://github.com/Trapar-waves/vue-tailwind) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-16: A Vue 3 project with Tailwind CSS, Rsbuild and modern development tools.
* [@trapar-waves/react-mantine-tailwind](https://github.com/Trapar-waves/react-mantine-tailwind) ⭐ 2 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-22: A React template integrating Mantine UI and Tailwind CSS for modern web development.
* [vue-nestjs-ssr-starter](https://github.com/pikadun/vue-nestjs-ssr-starter) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-12: A lightweight full-stack SSR starter with Vue 3, NestJS, Fastify, PrimeVue, and Rsbuild.
* [react-nestjs-ssr-starter](https://github.com/pikadun/react-nestjs-ssr-starter) ⭐ 2 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-16: A lightweight full-stack starter for server-side rendering with NestJS and React.
* [rsbuild-vue-starter](https://github.com/logue/rsbuild-vue-starter) ⭐ 1 | 🐛 1 | 🌐 Vue | 📅 2026-08-14: A simple starter template using the Vue + Vue-router + Pinia stack. Includes built-in formatting with rslint and testing with rstest.
* [@trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-16: A modern UI development template integrating React and Tailwind CSS, with Rsbuild, TypeScript, ESLint.
* [rsbuild-react-chakra-starter](https://github.com/sozonome/rsbuild-react-chakra-starter): initialize react app with rsbuild, Chakra UI and TypeScript setup. Configured with awesome toolings: Biome, Husky + Lint-Staged, Commitlint, and Turbo.

### Rslib Starter

* [ts-lib-starter](https://github.com/ulivz/ts-lib-starter) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-07: A hassle-free TS library template, powered by Rslib.
* [rslib-npm-template](https://github.com/LLmoskk/rslib-npm-template) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-07: A starter template for developing React components with Rslib, featuring automated versioning and publishing using semantic-release.
* [@trapar-waves/llm-template](https://github.com/Trapar-waves/llm-template) ⭐ 3 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-22: A template for LLM development integrating AI tools, TypeScript, Zod, and Rslib.
* [rstack-library-starter](https://github.com/logue/rstack-library-starter) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-17: Production-ready starter for Rsbuild/Rslib library development. Built on Rstack (Rspack, Rslib, Rstest, Rslint), with structured documentation patterns (AGENTS.md, PLAN.md), comprehensive testing, and a minimal Pico.css demo site. Validated across multiple libraries.
* [web-component-starter](https://github.com/holyfata/web-component-starter): A starter for developing Web components with Rslib, featuring using stencil and useful both in React and Vue.

## Plugins

### Rspack Plugins

* [@unocss/webpack](https://github.com/unocss/unocss/tree/main/packages-integrations/webpack) ⭐ 18,932 | 🐛 155 | 🌐 TypeScript | 📅 2026-08-21: Plugin for UnoCSS.
* [webpack-bundle-analyzer](https://github.com/webpack-contrib/webpack-bundle-analyzer) ⭐ 12,660 | 🐛 27 | 🌐 JavaScript | 📅 2026-08-21: Visualize size of webpack output files with an interactive zoomable treemap.
* [@vanilla-extract/webpack-plugin](https://github.com/vanilla-extract-css/vanilla-extract) ⭐ 10,407 | 🐛 72 | 🌐 TypeScript | 📅 2026-08-07: Integrating vanilla-extract with webpack / Rspack.
* [code-inspector-plugin](https://github.com/zh-lx/code-inspector) ⭐ 3,010 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-31: Click an element on the page, it can automatically open the editor and position the cursor to the source code of the element.
* [@module-federation/enhanced](https://github.com/module-federation/core/tree/main/packages/enhanced) ⭐ 2,619 | 🐛 61 | 🌐 JavaScript | 📅 2026-08-21: Provides enhanced features for Module Federation.
* [webpackbar](https://github.com/unjs/webpackbar) ⭐ 2,092 | 🐛 29 | 🌐 TypeScript | 📅 2026-08-21: Elegant ProgressBar and Profiler for Rspack.
* [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) ⚠️ Archived: Remove your build folder before building.
* [@serwist/webpack-plugin](https://github.com/serwist/serwist) ⭐ 1,466 | 🐛 11 | 🌐 TypeScript | 📅 2026-07-22: generate a manifest of local files for progressive web apps.
* [compression-webpack-plugin](https://github.com/webpack-contrib/compression-webpack-plugin) ⭐ 1,424 | 🐛 13 | 🌐 JavaScript | 📅 2026-08-12: Prepare compressed versions of assets to serve them with Content-Encoding.
* [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) ⭐ 1,295 | 🐛 20 | 🌐 JavaScript | 📅 2026-03-07: A secure plugin that supports dotenv and other environment variables.
* [@rsdoctor/rspack-plugin](https://github.com/web-infra-dev/rsdoctor/tree/main/packages/rspack-plugin) ⭐ 1,140 | 🐛 26 | 🌐 TypeScript | 📅 2026-08-22: An Rspack plugin for integrating Rsdoctor.
* [sonda](https://github.com/filipsobol/sonda) ⭐ 784 | 🐛 11 | 🌐 TypeScript | 📅 2026-08-09: Visualizer and analyzer for JavaScript and CSS bundles.
* [case-sensitive-paths-webpack-plugin](https://github.com/Urthen/case-sensitive-paths-webpack-plugin) ⭐ 427 | 🐛 43 | 🌐 JavaScript | 📅 2023-01-07: Enforces case sensitive paths of all required modules.
* [css-minimizer-webpack-plugin](https://github.com/webpack-contrib/css-minimizer-webpack-plugin) ⚠️ Archived: Uses cssnano to optimize and minify your CSS.
* [node-polyfill-webpack-plugin](https://github.com/Richienb/node-polyfill-webpack-plugin) ⭐ 302 | 🐛 14 | 🌐 JavaScript | 📅 2024-12-04: Polyfill Node.js core modules.
* [@sentry/webpack-plugin](https://github.com/getsentry/sentry-javascript-bundler-plugins) ⭐ 177 | 🐛 26 | 🌐 TypeScript | 📅 2026-07-10: Provides source map and release management support for Sentry.
* [@datadog/rspack-plugin](https://github.com/DataDog/build-plugins) ⭐ 110 | 🐛 40 | 🌐 TypeScript | 📅 2026-08-21: A Rspack plugin to interact with Datadog from your builds.
* [rspack-plugin-virtual-module](https://github.com/rstackjs/rspack-plugin-virtual-module) ⚠️ Archived: An Rspack plugin that allows you to create virtual modules.
* [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin) ⭐ 28 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-23: A plugin to use workbox in Rspack.
* [ts-checker-rspack-plugin](https://github.com/rstackjs/ts-checker-rspack-plugin) ⭐ 28 | 🐛 6 | 🌐 TypeScript | 📅 2026-08-21: Runs TypeScript type checker on a separate process.
* [@rspack/plugin-react-refresh](https://github.com/rstackjs/rspack-plugin-react-refresh) ⭐ 20 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-21: Support React Fast Refresh.
* [html-rspack-plugin](https://github.com/rstackjs/html-rspack-plugin) ⭐ 19 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-18: Generate files to serve your Rspack bundles.
* [html-rspack-plugin](https://github.com/rstackjs/html-rspack-plugin) ⭐ 19 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-18: Simplifies creation of HTML files to serve your bundles.
* [rspack-manifest-plugin](https://github.com/rstackjs/rspack-manifest-plugin) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-12: An Rspack plugin for generating an asset manifest.
* [rspack-plugin-mock](https://github.com/pengzhanbo/rspack-plugin-mock) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-10: Rspack and Rsbuild plugin for API mock dev server.
* [rspack-deno-plugin](https://github.com/LonelySnowman/rspack-deno-plugin) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-18: Make Rspack run correctly in the deno environment.
* [rspack-plugin-retry-chunk-load](https://github.com/khodorammar/rspack-plugin-retry-chunk-load) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-09-14 Retry loading of chunks that failed to load.
* [@vue-devtools-rstack/rspack](https://github.com/OskarLebuda/vue-devtools-rstack/tree/main/packages/rspack) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23: Integrates Vue DevTools with raw Rspack setups, with feature parity with `vite-plugin-vue-devtools`.
* [@rspack/plugin-preact-refresh](https://github.com/rstackjs/rspack-plugin-preact-refresh) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-21: Support Preact Refresh.
* [eslint-rspack-plugin](https://github.com/rstackjs/eslint-rspack-plugin) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-15: Rspack plugin to run ESLint checks during the compilation.
* [react-cosmos-plugin-rspack](https://github.com/birchill/react-cosmos-plugin-rspack/) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-14: Allows building / running React Cosmos using Rspack.
* [typia-rspack-plugin](https://github.com/colinaaa/typia-rspack-plugin) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-02: A Rspack plugin for `typia` - TypeScript transformer for runtime type checking and validation.
* [inject-manifest-plugin](https://github.com/tobua/inject-manifest-plugin) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-18: Injects a Workbox PWA manifest into a Service Worker.
* [rspack-plugin-cli-copy](https://github.com/rstackjs/rspack-plugin-cli-copy) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20: Start the project and automatically copy the network URL of the terminal.
* [rspack-circular-dependency-plugin](https://github.com/Sunny-117/rspack-circular-dependency-plugin) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-19: Detect circular dependencies in modules compiled with Rspack.
* [rspack-s3-plugin](https://github.com/ts-codeworks/rspack-s3-plugin) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-25: A Rspack plugin for uploading compiled assets to Amazon S3 after build.
* [rtlcss-rspack-plugin](https://github.com/cbbfcd/rtlcss-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-20: Rspack plugin to create a second css bundle, processed to be rtl.
* [html-inline-css-rspack-plugin](https://github.com/cbbfcd/html-inline-css-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-20 A Rspack plugin to convert external stylesheets into embedded stylesheets.
* [html-rspack-skip-assets-plugin](https://github.com/cbbfcd/html-rspack-skip-assets-plugin) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-20 Adapt `html-webpack-skip-assets-plugin` to Rspack.
* [compression-rspack-plugin](https://github.com/ramon-villain/compression-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-30: Rust-native parallel compression plugin for Rspack. Drop-in replacement for compression-webpack-plugin with gzip, brotli, deflate, and deflateRaw — all parallelized across CPU cores via Rust + rayon.
* [@golar-rstack/rspack](https://github.com/OskarLebuda/golar-rstack-plugin/tree/main/packages/rspack) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28: Runs golar type checking and type-aware linting in a separate process as an Rspack plugin.
* [rspack-plugin-solid-svg](https://github.com/solarlime/rspack-plugin-solid-svg) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-14: Rspack plugin for transforming SVG files into SolidJS components.
* [rspack-plugin-svg-sprite](https://github.com/yichenzhu1337/rspack-plugin-svg-sprite): SVG sprite plugin for Rspack — drop-in replacement for svg-sprite-loader.
* [@nx/module-federation](https://nx.dev/nx-api/module-federation/documents/nx-module-federation-plugin): Includes several Rspack plugins for Nx and Module Federation.
* [zephyr-rspack-plugin](https://www.npmjs.com/package/zephyr-rspack-plugin): An Rspack plugin for deploying applications with Zephyr Cloud.
* [@octanejs/rspack-plugin](https://octanejs.dev/docs/build-tools#rspack): Rspack loader and compiler plugin for Octane TSRX source.

### Rspack Loaders

Rspack and Rsbuild support most of the webpack loaders, such as:

* [@tailwindcss/webpack](https://github.com/tailwindlabs/tailwindcss/tree/main/packages/%40tailwindcss-webpack) ⭐ 97,288 | 🐛 56 | 🌐 TypeScript | 📅 2026-08-14: A webpack loader for Tailwind CSS v4.
* [@mdx-js/loader](https://github.com/mdx-js/mdx/tree/main/packages/loader) ⭐ 19,748 | 🐛 20 | 🌐 JavaScript | 📅 2026-08-21: Loader for MDX.
* [@svgr/webpack](https://github.com/gregberge/svgr/tree/main/packages/webpack) ⭐ 11,053 | 🐛 148 | 🌐 TypeScript | 📅 2026-03-01: Loader for SVGR.
* [babel-loader](https://github.com/babel/babel-loader) ⭐ 4,838 | 🐛 65 | 🌐 JavaScript | 📅 2026-08-04: Transpiling JavaScript files using Babel.
* [css-loader](https://github.com/webpack-contrib/css-loader) ⭐ 4,320 | 🐛 33 | 🌐 JavaScript | 📅 2026-08-12: Interprets @import and url() in CSS files and resolve them.
* [sass-loader](https://github.com/webpack-contrib/sass-loader) ⭐ 3,891 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-20: Compiles Sass/SCSS files to CSS.
* [postcss-loader](https://github.com/webpack-contrib/postcss-loader) ⭐ 2,843 | 🐛 10 | 🌐 JavaScript | 📅 2026-08-12: Loader to process CSS with PostCSS.
* [style-loader](https://github.com/webpack-contrib/style-loader) ⭐ 1,666 | 🐛 10 | 🌐 JavaScript | 📅 2026-08-12: Inject CSS into the DOM.
* [@vue-vine/rspack-loader](https://github.com/vue-vine/vue-vine) ⭐ 1,444 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-21: Rspack loader for Vue Vine.
* [less-loader](https://github.com/webpack-contrib/less-loader) ⭐ 958 | 🐛 5 | 🌐 JavaScript | 📅 2026-08-12: Compiles Less to CSS.
* [svelte-loader](https://github.com/sveltejs/svelte-loader) ⭐ 604 | 🐛 23 | 🌐 JavaScript | 📅 2026-04-02: Loader for svelte components.
* [svg-react-loader](https://github.com/jhamlet/svg-react-loader) ⚠️ Archived: Turn SVGs into React Components.
* [stylus-loader](https://github.com/webpack-contrib/stylus-loader) ⭐ 492 | 🐛 6 | 🌐 JavaScript | 📅 2026-08-12: Compiles Stylus to CSS.
* [source-map-loader](https://github.com/webpack-contrib/source-map-loader) ⚠️ Archived: Extracts source maps from existing source files.
* [svgo-loader](https://github.com/svg/svgo-loader) ⭐ 310 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-26: Loader for SVGO.
* [yaml-loader](https://github.com/eemeli/yaml-loader) ⭐ 153 | 🐛 7 | 🌐 JavaScript | 📅 2026-05-22: Allows importing YAML files as JS objects.
* [react-compiler-webpack](https://github.com/SukkaW/react-compiler-webpack) ⭐ 121 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20: The webpack / Rspack loader for React Compiler.
* [rsbuild-plugin-markdown-loader](https://github.com/aliezzahn/rsbuild-plugin-markdown-loader) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20: Importing and rendering Markdown files as React components or pure HTML.
* [oxc-webpack-loader](https://github.com/oxc-project/oxc-webpack-loader) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-19: Uses Oxc for fast JavaScript and TypeScript transformation.
* [rspack-vue-loader](https://github.com/rstackjs/rspack-vue-loader) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-21: Vue loader for Rspack.
* [worker-rspack-loader](https://github.com/rstackjs/worker-rspack-loader) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-08-21: An Rspack loader that registers a script as a Web Worker.
* [html-loader](https://www.npmjs.com/package/html-loader): Exports HTML as string.
* [imports-loader](https://www.npmjs.com/package/imports-loader): Use modules that depend on specific global variables.
* [coffee-loader](https://www.npmjs.com/package/coffee-loader): Compile CoffeeScript to JavaScript.
* [node-loader](https://www.npmjs.com/package/node-loader): Allows to connect native node modules with .node extension.

### Rsbuild Plugins

#### For React

* [rsbuild-plugin-react-router](https://github.com/rstackjs/rsbuild-plugin-react-router) ⭐ 137 | 🐛 8 | 🌐 TypeScript | 📅 2026-07-29: Provides seamless integration with React Router.
* [rsbuild-plugin-rsc](https://github.com/rstackjs/rsbuild-plugin-rsc) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: React Server Components (RSC) support for Rsbuild.
* [rsbuild-plugin-react-inspector](https://github.com/hunghg255/rsbuild-plugin-react-inspector) ⭐ 13 | 🐛 0 | 🌐 JavaScript | 📅 2025-04-20: Allows automatic jumping to the local IDE when clicking on a browser element.
* [@rsbuild/plugin-styled-components](https://github.com/rstackjs/rsbuild-plugin-styled-components) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-21: Provides compile-time support for styled-components.
* [rsbuild-react-generate-pages](https://github.com/hunghg255/rsbuild-react-generate-pages) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-20: Generate pages for React app based on the directory structure and `react-router-dom` configuration.
* [@rsbuild/plugin-react](https://rsbuild.rs/plugins/list/plugin-react): Provides support for React.
* [@rsbuild/plugin-svgr](https://rsbuild.rs/plugins/list/plugin-svgr): Support convert SVG to React components.

#### For Vue

* [@vue-vine/rsbuild-plugin](https://github.com/vue-vine/vue-vine) ⭐ 1,444 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-21: Rsbuild plugin for Vue Vine.
* [@vizejs/rspack-plugin](https://github.com/ubugeeei/vize) ⭐ 877 | 🐛 35 | 🌐 Rust | 📅 2026-08-23: High-Performance Vue.js Toolchain in Rust.
* [@rsbuild/plugin-vue-jsx](https://github.com/rstackjs/rsbuild-plugin-vue-jsx) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15: Provides support for Vue 3 JSX / TSX syntax.
* [@vue-devtools-rstack/rsbuild](https://github.com/OskarLebuda/vue-devtools-rstack/tree/main/packages/rsbuild) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-23: Integrates Vue DevTools with Rsbuild, with feature parity with `vite-plugin-vue-devtools`.
* [rsbuild-plugin-vue-inspector](https://github.com/hunghg255/rsbuild-plugin-vue-inspector) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-31: Allows automatic jumping to the local IDE when clicking on a browser element.
* [@rsbuild/plugin-vue2-jsx](https://github.com/rstackjs/rsbuild-plugin-vue2-jsx) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-12: Provides support for Vue 2 JSX / TSX syntax.
* [rsbuild-plugin-vue-legacy](https://github.com/skymoonya/rsbuild-plugin-vue-legacy) ⭐ 7 | 🐛 2 | 🌐 Vue | 📅 2024-04-10: Support for Vue versions below 2.7 by setting an alias for `vue`.
* [@rsbuild/plugin-vue2](https://github.com/rstackjs/rsbuild-plugin-vue2) ⭐ 6 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: Provides support for Vue 2 SFC (Single File Components).
* [rsbuild-plugin-unplugin-vue](https://github.com/rstackjs/rsbuild-plugin-unplugin-vue) ⭐ 6 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-21: Integrates `unplugin-vue` for Vue SFC compilation.
* [rspack-plugin-svg](https://github.com/fuxichen/rspack-plugin-svg) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2024-10-21: Rsbuild plugin to load SVG files as Vue components, using SVGO for optimization.
* [@mutsuntsai/rsbuild-plugin-vue-ssg](https://github.com/mutsuntsai/rsbuild-plugin-vue-ssg) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-29: Generate Vue SSG contents and inject those into HTML for Rsbuild.
* [@rsbuild/plugin-vue](https://rsbuild.rs/plugins/list/plugin-vue): Provides support for Vue 3 SFC (Single File Components).

#### For Preact

* [@rsbuild/plugin-preact](https://rsbuild.rs/plugins/list/plugin-preact): Provides support for Preact.

#### For Svelte

* [@rsbuild/plugin-svelte](https://rsbuild.rs/plugins/list/plugin-svelte): Provides support for Svelte components (`.svelte` files).
* [rsbuild-plugin-svelte-inspector](https://github.com/hunghg255/rsbuild-plugin-svelte-inspector) ⭐ 8 | 🐛 0 | 🌐 JavaScript | 📅 2024-05-31: Allows automatic jumping to the local IDE when clicking on a browser element.

#### For Solid

* [@rsbuild/plugin-solid](https://rsbuild.rs/plugins/list/plugin-solid): Provides support for Solid.

#### For Lynx

* [lynxjs-app-config-plugin](https://github.com/HimanshuKumarDutt094/lynxjs-app-config-plugin) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-11: Rsbuild plugin to inject application icons, permissions and minimal app config changes into Android / iOS project folders.
* [relog-rsbuild-plugin](https://github.com/nanofuxion/relog-rsbuild-plugin) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-09: Allows you to intercept `console.log()` calls from your LynxJS app running on a device or emulator and send them back to the Rsbuild dev server.
* [ngrok-rsbuild-plugin](https://github.com/nanofuxion/ngrok-rsbuild-plugin) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-09: Expose your Rsbuild dev server over the internet via ngrok — built for use with the LynxJS app.

#### Common

* [@seed-design/rsbuild-plugin](https://github.com/daangn/seed-design) ⭐ 1,059 | 🐛 73 | 🌐 TypeScript | 📅 2026-08-22: An Rsbuild plugin for the Seed design system.
* [rsbuild-plugin-dts](https://github.com/web-infra-dev/rslib/tree/main/packages/plugin-dts) ⭐ 1,002 | 🐛 28 | 🌐 TypeScript | 📅 2026-08-22: Generate TypeScript declaration files.
* [rsbuild-plugin-tailwindcss](https://github.com/rstackjs/rsbuild-plugin-tailwindcss) ⭐ 54 | 🐛 20 | 🌐 TypeScript | 📅 2026-08-19: An Rsbuild plugin to integrate with Tailwind CSS.
* [@webx-kit/rsbuild-plugin](https://github.com/tmkx/webx-kit) ⭐ 35 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28: Rsbuild plugin for Web eXtension development.
* [rsbuild-plugin-css-optimizer](https://github.com/aliezzahn/rsbuild-plugin-css-optimizer) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-04: Customize CSS minification, allowing you to choose between cssnano (JavaScript-based) or Lightning CSS (Rust-based) for high-performance CSS compression.
* [@rsbuild/plugin-image-compress](https://github.com/rstackjs/rsbuild-plugin-image-compress) ⭐ 25 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-20: Compress the image assets.
* [rsbuild-plugin-publint](https://github.com/rstackjs/rsbuild-plugin-publint) ⭐ 22 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21: Run `publint` to lint npm packages after the build.
* [@rsbuild/plugin-check-syntax](https://github.com/rstackjs/rsbuild-plugin-check-syntax) ⭐ 21 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: Used to analyze the syntax compatibility of artifacts, to see if there are any advanced syntaxes that may cause compatibility issues.
* [@rsbuild/plugin-node-polyfill](https://github.com/rstackjs/rsbuild-plugin-node-polyfill) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: Used to inject polyfills of Node core modules in the browser side.
* [@rsbuild/plugin-source-build](https://github.com/rstackjs/rsbuild-plugin-source-build) ⭐ 18 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-20: This plugin is designed for the monorepo scenario. It supports referencing source code from other subdirectories and performs build and hot update.
* [rsbuild-plugin-web-extension](https://github.com/filc-dev/rsbuild-plugin-web-extension) ⭐ 16 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-04: Rsbuild plugin for Chrome/web extension.
* [rsbuild-plugin-wasmpack](https://github.com/im-neiru/rsbuild-plugin-wasmpack) ⭐ 15 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-25: compile Rust crates to WebAssembly using wasm-pack.
* [rsbuild-plugin-print](https://github.com/hunghg255/rsbuild-plugin-print) ⭐ 14 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-03: Print text, show host with qrcode.
* [@rsbuild/plugin-type-check](https://github.com/rstackjs/rsbuild-plugin-type-check) ⭐ 13 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-12: Used to run TypeScript type checker on a separate process.
* [rsbuild-plugin-devtools-json](https://github.com/rstackjs/rsbuild-plugin-devtools-json) ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-12: Generating `com.chrome.devtools.json` on the fly in the dev server.
* [@rsbuild/plugin-assets-retry](https://github.com/rstackjs/rsbuild-plugin-assets-retry) ⭐ 10 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21: Used to automatically resend requests when static assets fail to load.
* [@rsbuild/plugin-typed-css-modules](https://github.com/rstackjs/rsbuild-plugin-typed-css-modules) ⭐ 10 | 🐛 5 | 🌐 TypeScript | 📅 2026-08-20: Generate TypeScript declaration files for CSS Modules.
* [rsbuild-plugin-console-debug](https://github.com/hunghg255/rsbuild-plugin-console-debug) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2024-05-31: Output debug information in the console.
* [@rsbuild/plugin-mdx](https://github.com/rstackjs/rsbuild-plugin-mdx) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: Provide support for MDX.
* [rsbuild-plugin-virtual-module](https://github.com/rstackjs/rsbuild-plugin-virtual-module) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-14: Used to create virtual modules with loader API.
* [rsbuild-plugin-block-imports](https://github.com/malekabdelkader/rsbuild-plugin-block-imports) ⭐ 8 | 🐛 3 | 🌐 TypeScript | 📅 2026-03-17: Rsbuild plugin to detect and block forbidden imports in Module Federation builds.
* [@rsbuild/plugin-rem](https://github.com/rstackjs/rsbuild-plugin-rem) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-20: Implements the rem adaptive layout for mobile pages.
* [@rsbuild/plugin-yaml](https://github.com/rstackjs/rsbuild-plugin-yaml) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-20: Used to import YAML files and convert them into JavaScript objects.
* [rsbuild-plugin-open-graph](https://github.com/rstackjs/rsbuild-plugin-open-graph) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21: Generate Open Graph meta tags.
* [rsbuild-plugin-workspace-dev](https://github.com/rstackjs/rsbuild-plugin-workspace-dev) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15: Start monorepo sub-projects in topological order.
* [rsbuild-plugin-google-analytics](https://github.com/rstackjs/rsbuild-plugin-google-analytics) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21: Setup Google Analytics in your website.
* [rsbuild-plugin-html-minifier-terser](https://github.com/rstackjs/rsbuild-plugin-html-minifier-terser) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15: An Rsbuild plugin to use `html-minifier-terser` to minify the HTML outputs.
* [rsbuild-plugin-glsl](https://github.com/sakitam-fdd/rsbuild-plugin-glsl) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-17: An Rsbuild plugin to import inline (and compress) GLSL shader.
* [rsbuild-plugin-rempa](https://github.com/sumy7/rsbuild-plugin-rempa) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-10: A Rsbuild plugin designed to collect pages and generate a Multi-Page Application (MPA).
* [rsbuild-plugin-pwa](https://github.com/s-r-x/rsbuild-plugin-pwa) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-22: Zero-config PWA support for rsbuild
* [@rsbuild/plugin-basic-ssl](https://github.com/rstackjs/rsbuild-plugin-basic-ssl) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-20: Generate an untrusted, self-signed certificate for the HTTPS server.
* [rsbuild-plugin-generate-file](https://github.com/sumy7/rsbuild-plugin-generate-file) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-02: Generate static file and write them to dist folder after packaging.
* [plugin-sails-content](https://github.com/sailscastshq/sails-content/packages/plugin-sails-content) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-30: Rsbuild plugin for [Sails Content](https://docs.sailscasts.com/content/).
* [rsbuild-plugin-i18next-extractor](https://github.com/rstackjs/rsbuild-plugin-i18next-extractor) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-24: An Rsbuild plugin using [i18next-cli](https://github.com/i18next/i18next-cli) ⭐ 232 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-20 to extract i18n translations.
* [@rsbuild/plugin-eslint](https://github.com/rstackjs/rsbuild-plugin-eslint) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-22: Used to run ESLint checks during the compilation.
* [@rsbuild/plugin-css-minimizer](https://github.com/rstackjs/rsbuild-plugin-css-minimizer) ⭐ 4 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-15: Used to customize CSS minimizer, switch to [cssnano](https://cssnano.co/) or other tools for CSS compression.
* [@rsbuild/plugin-umd](https://github.com/rstackjs/rsbuild-plugin-umd) ⭐ 4 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-12: Used to build outputs in UMD format.
* [@rsbuild/plugin-toml](https://github.com/rstackjs/rsbuild-plugin-toml) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15: Used to import TOML files and convert them into JavaScript objects.
* [rsbuild-plugin-posthog](https://github.com/m1911star/rsbuild-plugin-posthog) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2024-04-08: Rsbuild plugin for PostHog.
* [rsbuild-plugin-stylelint](https://github.com/zalishchuk/rsbuild-plugin-stylelint) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-28: Used to run Stylelint checks during the compilation.
* [rsbuild-plugin-ejs](https://github.com/rstackjs/rsbuild-plugin-ejs) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-15: Provide support for the EJS template engine.
* [rsbuild-plugin-arethetypeswrong](https://github.com/colinaaa/rsbuild-plugin-arethetypeswrong) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-12: Checking TypeScript type definitions with `arethetypeswrong`.
* [rsbuild-plugin-protobufjs](https://github.com/baranwang/rsbuild-plugin-protobufjs) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2026-05-24: An Rsbuild plugin that integrates `protobufjs`.
* [rsbuild-plugin-mcp](https://github.com/colinaaa/rsbuild-plugin-mcp) ⭐ 3 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-21: Rsbuild plugin that enables a MCP server for your Rsbuild app to provide information about your setup and modules graphs.
* [rsbuild-plugin-compression](https://github.com/s-r-x/rsbuild-plugin-compression) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-06: Compress the assets using gzip, brotli or zstd.
* [rsbuild-plugin-oxlint](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/oxlint) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04: Plugin for Integrating Oxlint into the Rsbuild Build Process.
* [rsbuild-plugin-rslint](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/rslint) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04: Plugin for Integrating Rslint into the Rsbuild Build Process.
* [rsbuild-plugin-biome](https://github.com/robertpanvip/rsbuild-plugin-lint/tree/main/packages/biome) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-04: Plugin for Integrating Biome into the Rsbuild Build Process.
* [@rsbuild/plugin-pug](https://github.com/rstackjs/rsbuild-plugin-pug) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-15: Provides support for the Pug template engine.
* [rsbuild-plugin-web-ext](https://github.com/xbzhang2020/rsbuild-plugin-web-ext/tree/main/packages/rsbuild) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-08: A Rsbuild plugin for developing and building browser extensions.
* [rsbuild-plugin-auto-alias](https://github.com/jwyGithub/rsbuild-plugin-auto-alias) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-20: Automatically generate alias based on path.
* [rsbuild-plugin-arco](https://github.com/zhmushan/rsbuild-plugin-arco) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-03-20: Rsbuild plugins for Arco Design.
* [rsbuild-plugin-cdn-import](https://github.com/fuxichen/rsbuild-plugin-cdn-import) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-27: Import modules from CDN with Rsbuild plugin.
* [@golar-rstack/rsbuild](https://github.com/OskarLebuda/golar-rstack-plugin/tree/main/packages/rsbuild) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28: Runs golar type checking and type-aware linting in a separate process as an Rsbuild plugin.
* [rsbuild-plugin-monaco-editor-nls](https://github.com/zackshen/rsbuild-plugin-monaco-editor-nls) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-06: An Rsbuild plugin to localize monaco-editor.
* [rsbuild-plugin-aws-lambda](https://github.com/wxiaoyun/rsbuild-plugin-aws-lambda) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-02: An Rsbuild plugin to configure rsbuild to bundle js assets suitable for AWS Lambda.
* [@devjskit/rsbuild-plugin-langs](https://github.com/devjskit/rsbuild-plugin-langs) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-14: Extract content from JSON files and merge into a multi-language file.
* [rsbuild-plugin-iconify](https://github.com/pathscale/iconify-preload) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-15: A Rsbuild plugin that automatically generates optimized CSS with embedded SVG icons from Iconify.
* [@plugin-cra-proxy/rsbuild](https://github.com/robertpanvip/plugin-cra-proxy/tree/main/packages/rsbuild) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03: A development proxy plugin for Rsbuild, mimicking Create React App proxy behavior.
* [@rsbuild/plugin-babel](https://rsbuild.rs/plugins/list/plugin-babel): Provides support for Babel transpilation capabilities.
* [@rsbuild/plugin-sass](https://rsbuild.rs/plugins/list/plugin-sass): Sass plugin for Rsbuild.
* [@rsbuild/plugin-less](https://rsbuild.rs/plugins/list/plugin-less): Less plugin for Rsbuild.
* [@rsbuild/plugin-stylus](https://rsbuild.rs/plugins/list/plugin-stylus): Use Stylus as the CSS preprocessor.
* [@rsbuild/plugin-tailwindcss](https://rsbuild.rs/plugins/list/plugin-tailwindcss): Integrates Tailwind CSS v4 in Rsbuild.
* [rsbuild-plugin-marko](https://github.com/ipseonet/rsbuild-plugin-marko): An Rsbuild plugin to provide support for the Marko template engine.
* [rsbuild-plugin-svg-sprite](https://github.com/yichenzhu1337/rspack-plugin-svg-sprite): SVG sprite plugin for Rsbuild — drop-in replacement for svg-sprite-loader.
* [@module-federation/rsbuild-plugin](https://module-federation.io/guide/basic/rsbuild): An Rsbuild plugin for integrating Module Federation v2.
* [zephyr-rsbuild-plugin](https://www.npmjs.com/package/zephyr-rsbuild-plugin): An Rsbuild plugin for deploying applications with Zephyr Cloud.
* [@octanejs/rsbuild-plugin](https://octanejs.dev/docs/build-tools#rsbuild): Rsbuild metaframework plugin for Octane, including routing, SSR, hydration, and production builds.

### Rspress Plugins

* [@rspress/plugin-typedoc](https://rspress.rs/plugin/official-plugins/typedoc): Integrate [TypeDoc](https://github.com/TypeStrong/typedoc) ⭐ 8,446 | 🐛 17 | 🌐 TypeScript | 📅 2026-07-13, used to generate API documentation of TS module automatically.
* [@rspress/plugin-rss](https://rspress.rs/plugin/official-plugins/rss): Generates RSS files for specific document pages with [feed](https://github.com/jpmonette/feed) ⭐ 1,407 | 🐛 29 | 🌐 TypeScript | 📅 2026-07-06.
* [rspress-plugin-align-image](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-align-image) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to align images in markdown.
* [rspress-plugin-directives](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-directives) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin for custom directives support.
* [rspress-plugin-file-tree](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-file-tree) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin that add tree view for file structure display.
* [rspress-plugin-gh-pages](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-gh-pages) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to add support for automatic deployment to GitHub Pages.
* [rspress-plugin-google-analytics](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-google-analytics) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin for Google Analytics integration.
* [rspress-plugin-vercel-analytics](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-vercel-analytics) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin for Vercel Analytics integration.
* [rspress-plugin-katex](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-katex) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to add support for rendering math equations using [KaTeX](https://katex.org/).
* [rspress-plugin-live2d](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-live2d) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin for live2d, powered by [on-my-live2d](https://oml2d.com/).
* [rspress-plugin-mermaid](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-mermaid) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to render [Mermaid](https://mermaid.js.org/#/) diagrams in markdown files.
* [rspress-plugin-reading-time](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-reading-time) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to display reading time for your document pages.
* [rspress-plugin-supersub](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-supersub) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin to add superscript(`<super></super>`) and subscript(`<sub></sub>`) support.
* [rspress-plugin-toc](https://github.com/rstackjs/rspress-plugins/tree/main/packages/rspress-plugin-toc) ⭐ 13 | 🐛 4 | 🌐 TypeScript | 📅 2026-08-04: Rspress plugin that injects a table of contents into the page.
* [rspress-plugin-shiki](https://github.com/hunghg255/rspress-plugin-shiki) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2024-04-01: Rspress plugin shiki with transformer.
* [rspress-plugin-remote-page](https://github.com/ulivz/rspress-plugin-remote-page) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2023-10-26: Load remote markdown file (e.g. README.md) onto your website.
* [rspress-plugin-mention-github](https://github.com/hunghg255/rspress-plugin-mention-github) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2024-06-08: Rspress plugin mention github user, or any link.
* [rspress-plugin-font-open-sans](https://github.com/rstackjs/rspress-plugin-font-open-sans) ⭐ 6 | 🐛 1 | 🌐 CSS | 📅 2026-08-12: Use Open Sans as the default font in your Rspress website.
* [rspress-plugin-changelog](https://github.com/baranwang/rspress-plugin-changelog) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-26: Generates changelog pages, fetching release information from GitHub and GitLab repositories.
* [rspress-plugin-translate](https://github.com/byteHulk/rspress-plugin-translate) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2024-01-03: Automatically translate your content behind the scenes using GPT's.
* [rspress-plugin-sitemap](https://github.com/jl917/rspress-plugin-sitemap) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-28: Automatically generate SEO-related sitemaps.
* [rspress-language-tabs](https://github.com/maccuaa/rspress-language-tabs) ⭐ 5 | 🐛 1 | 🌐 MDX | 📅 2026-08-21: An Rspress component for creating tabbed code examples with programming language icons.
* [rspress-plugin-font-figtree](https://github.com/maccuaa/rspress-plugin-font-figtree) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-21: Use Figtree as the default font in your Rspress website.
* [rspress-plugin-pdf-generator](https://github.com/MaxtuneLee/rspress-plugin-pdf-generator) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-16: Generates multi-language single-page or multi-page PDF documents from Rspress site during build process.
* [rspress-plugin-clarity](https://github.com/jl917/rspress-plugin-clarity) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2024-05-18: Rspress plugin for [Clarity](https://clarity.microsoft.com/) integration.
* [rspress-plugin-annotation-words](https://github.com/2heal1/rspress-plugin-annotation-words) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-04: An Rspress plugin to support annotation words.
* [rspress-plugin-auto-sidebar](https://github.com/buyfakett/rspress-plugin-auto-sidebar) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-24: Automatically generate the sidebar from the navbar configuration.
* [rspress-plugin-giscus](https://github.com/buyfakett/rspress-plugin-giscus) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-02-12: Integrate [giscus](https://github.com/giscus/giscus) ⭐ 12,051 | 🐛 126 | 🌐 TypeScript | 📅 2026-05-26 into Rspress, a comment system powered by GitHub Discussions.
* [rspress-plugin-blog-list](https://github.com/buyfakett/rspress-plugin-blog-list) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-24: Integrate blog list into Rspress.
* [@rspress/plugin-llms](https://rspress.rs/plugin/official-plugins/llms): Generates `llms.txt` and `llms-full.txt` files for your docs site.
* [@rspress/plugin-sitemap](https://rspress.rs/plugin/official-plugins/sitemap): Generates `sitemap.xml` for your website.
* [@rspress/plugin-client-redirects](https://rspress.rs/plugin/official-plugins/client-redirects): Supports client-side redirects for moved routes.
* [@rspress/plugin-api-docgen](https://rspress.rs/plugin/official-plugins/api-docgen): Generates API documentation from TypeScript declarations.
* [@rspress/plugin-preview](https://rspress.rs/plugin/official-plugins/preview): Support preview of code blocks in Markdown/MDX.
* [@rspress/plugin-playground](https://rspress.rs/plugin/official-plugins/playground): Provide a real-time playground to preview the code blocks in Markdown/MDX files.
* [@rspress/plugin-algolia](https://rspress.rs/plugin/official-plugins/algolia): Integrates Algolia DocSearch for site search.
* [@rspress/plugin-twoslash](https://rspress.rs/plugin/official-plugins/twoslash): Adds TypeScript Twoslash support for code blocks.
* [zephyr-rspress-plugin](https://www.npmjs.com/package/zephyr-rspress-plugin): An Rspress plugin for deploying applications with Zephyr Cloud.

### Unplugin

Rspack and Rsbuild support most of the [unplugin](https://github.com/unplugin), such as:

* [unplugin-icons](https://github.com/unplugin/unplugin-icons) ⭐ 4,933 | 🐛 86 | 🌐 TypeScript | 📅 2026-01-14: Access thousands of icons as components on-demand universally.
* [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components) ⭐ 4,291 | 🐛 152 | 🌐 TypeScript | 📅 2026-05-20: On-demand components auto importing for Vue.
* [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import) ⭐ 3,792 | 🐛 78 | 🌐 TypeScript | 📅 2026-08-03: Auto import APIs on-demand.
* [unplugin-vue-macros](https://github.com/vue-macros/vue-macros) ⭐ 1,984 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-23: Explore more macros and syntax sugar to Vue.
* [unplugin-dts](https://github.com/qmhc/unplugin-dts) ⭐ 1,528 | 🐛 21 | 🌐 TypeScript | 📅 2026-08-11: An unplugin that generates declaration files (\*.d.ts).
* [zod-compiler](https://github.com/gajus/zod-compiler) ⭐ 766 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-20: Compile Zod schemas into zero-overhead validation functions at build time.
* [unplugin-turbo-console](https://github.com/unplugin/unplugin-turbo-console) ⭐ 708 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-09: Improve the Developer Experience of console.
* [unplugin-macros](https://github.com/unplugin/unplugin-macros) ⭐ 278 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-17: Macros plugin for bundlers.
* [@intlify/unplugin-vue-i18n](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n) ⭐ 270 | 🐛 52 | 🌐 TypeScript | 📅 2026-08-20: unplugin for Vue I18n.
* [unplugin-element-plus](https://github.com/element-plus/unplugin-element-plus) ⭐ 252 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-15: Import Element Plus on demand.
* [unplugin-info](https://github.com/yjl9903/unplugin-info) ⭐ 112 | 🐛 8 | 🌐 TypeScript | 📅 2026-08-19: Export build information as a virtual module.
* [unplugin-ast](https://github.com/unplugin/unplugin-ast) ⭐ 99 | 🐛 2 | 🌐 TypeScript | 📅 2026-08-19: Manipulate the AST to transform your code.
* [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload) ⭐ 39 | 🐛 2 | 🌐 TypeScript | 📅 2024-12-15: Inject `<link rel="preload">` to your index.html based on your build assets. Need to be used with HTMLWebpackPlugin or HTMLRspackPlugin.
* [unplugin-favicons](https://github.com/anolilab/unplugin-favicons) ⭐ 10 | 🐛 12 | 🌐 TypeScript | 📅 2026-08-19: Generate favicons for your project with caching for blazing fast rebuilds.
* [unplugin-build-info](https://github.com/renzp94/unplugin-build-info) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-05: Print the build information on the console.
* [unplugin-build-meta](https://github.com/luxass/unplugin-build-meta) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-14: Import build metadata into your JavaScript/TypeScript projects.
* [unplugin-vue](https://www.npmjs.com/package/unplugin-vue): Transform Vue 3 SFC to JavaScript.
* [@stylexjs/unplugin](https://www.npmjs.com/package/@stylexjs/unplugin): Universal bundler plugin for StyleX.
* [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.
* [@tanstack/router-plugin](https://www.npmjs.com/package/@tanstack/router-plugin): Automatically generate configuration for TanStack Router.
* [@formatjs/unplugin](https://www.npmjs.com/package/@formatjs/unplugin): Universal build plugin for FormatJS.

## Rstest Adapters

* [@modern-js/adapter-rstest](https://github.com/web-infra-dev/modern.js/tree/main/packages/cli/adapter-rstest) ⭐ 5,038 | 🐛 46 | 🌐 TypeScript | 📅 2026-08-22: Rstest adapter for Modern.js configuration.
* [@rstest/adapter-rspack](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rspack) ⭐ 481 | 🐛 50 | 🌐 TypeScript | 📅 2026-08-21: Rstest adapter for Rspack configuration.
* [@rstest/adapter-rsbuild](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rsbuild) ⭐ 481 | 🐛 50 | 🌐 TypeScript | 📅 2026-08-21: Rstest adapter for Rsbuild configuration.
* [@rstest/adapter-rslib](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rslib) ⭐ 481 | 🐛 50 | 🌐 TypeScript | 📅 2026-08-21: Rstest adapter for Rslib configuration.

## Deployment

* [Zephyr Cloud](https://zephyr-cloud.io): A cloud-agnostic deployment platform offering sub-seconds `deploy from one command` experience.

## Libraries

* [Jetpack](https://github.com/KidkArolis/jetpack) ⭐ 1,307 | 🐛 0 | 🌐 JavaScript | 📅 2026-07-17: Jetpack wraps Rspack to create a smoother developer experience.
* [rspackify](https://github.com/SyMind/rspackify) ⭐ 43 | 🐛 3 | 🌐 TypeScript | 📅 2024-09-04: Experience lightning-fast builds by instantly switching from webpack to Rspack.
* [@rspack/resolver](https://github.com/rstackjs/rspack-resolver) ⭐ 42 | 🐛 20 | 🌐 Rust | 📅 2026-08-21: A Rust port of enhanced-resolve.
* [@rspack/dev-server](https://github.com/web-infra-dev/rspack-dev-server) ⭐ 41 | 🐛 4 | 🌐 JavaScript | 📅 2026-08-22: Dev server for Rspack, provides the same API as webpack-dev-server.
* [rspack-chain](https://github.com/rstackjs/rspack-chain) ⭐ 35 | 🐛 2 | 🌐 JavaScript | 📅 2026-08-21: A chaining API to generate and simplify the modification of Rspack configurations.
* [@rspack/lite-tapable](https://github.com/rstackjs/rspack-lite-tapable) ⭐ 9 | 🐛 3 | 🌐 JavaScript | 📅 2026-08-12: Lite weight tapable for Rspack.
* [Sails Shipwright](https://github.com/sailshq/sails-hook-shipwright) ⭐ 7 | 🐛 6 | 🌐 JavaScript | 📅 2026-05-27 - The modern asset pipeline for [Sails](https://sailsjs.com) powered by Rsbuild.
* [@rspack/dev-middleware](https://github.com/rstackjs/rspack-dev-middleware) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-08-21: A development middleware for Rspack.
* [rspack-merge](https://github.com/rstackjs/rspack-merge) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-14: Smart configuration merging for Rspack.
* [Spinpack](https://github.com/denniscual/spinpack) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2024-06-14: A CLI tool that turbocharges the developer server experience for CRA projects with Rspack.

## Blogs

### Rspack Team

Blogs from the Rspack team:

* [rspack.rs/blogs](https://rspack.rs/blog/)
* [web-infra-dev/blogs](https://github.com/web-infra-dev/blogs) ⭐ 38 | 🐛 0 | 📅 2025-09-04

### Community

English blogs:

* \[2026-06] [TanStack Start Adds First-Class Rsbuild Support](https://tanstack.com/blog/start-adds-rsbuild-support)
* \[2026-05] [Yelp Engineering: Optimizing Our Build Times by Migrating from Webpack to Rspack](https://engineeringblog.yelp.com/2026/05/optimizing-our-build-times-by-migrating-from-webpack-to-rspack.html)
* \[2026-03] [Rspress 2.0: AI-Native Documentation, Faster Startup and a Redesigned Theme](https://www.infoq.com/news/2026/03/rspress-docs-2-release)
* \[2026-01] [Transforming SVGs to Vue and Svelte Components: The SVGR Alternative for Rsbuild](https://hackernoon.com/transforming-svgs-to-vue-and-svelte-components-the-svgr-alternative-for-rsbuild)
* \[2025-12] [Goodbye Webpack, Hello Rspack (and 80% Faster Builds)](https://developers.mews.com/goodbye-webpack-hello-rspack-and-80-faster-builds/)
* \[2025-12] [The JavaScript Bundler Grand Prix](https://redmonk.com/kholterhoff/2025/12/16/javascript-bundler-grand-prix/)
* \[2025-08] [Rspack Introduces Rslint, a TypeScript-First Linter Written in Go](https://socket.dev/blog/rspack-introduces-rslint-a-typescript-first-linter-written-in-go)
* \[2025-08] [Question-based web performance analysis using rsdoctor/mcp-server](https://dev.to/husdev/question-based-web-performance-analysis-using-rsdoctormcp-server-325a)
* \[2025-08] [Rust Tools That Made Our Dev Team Productive Again](https://dev.to/programmerraja/rust-tools-that-made-our-dev-team-productive-again-479)
* \[2025-07] [Webpack to Rspack: A Deep Dive Into Our Build Time Breakthrough](https://dev.to/diwakersurya/webpack-to-rspack-a-deep-dive-into-our-build-time-breakthrough-3ih)
* \[2025-04] [My journey from Webpack to Vite and finally Rsbuild](https://www.ginkonote.com/users/flo/articles/my-journey-from-webpack-to-vite-and-finally-rsbuild@javascript)
* \[2025-04] [An Introduction to JavaScript Bundler Rspack](https://blog.appsignal.com/2025/04/16/an-introduction-to-javascript-bundler-rspack.html)
* \[2025-04] [Scaffolding New Apps With Angular Rspack](https://nx.dev/blog/scaffold-angular-rspack-applications):
* \[2025-03] [Using Rspack with Angular](https://nx.dev/blog/using-rspack-with-angular)
* \[2025-02] [Rspack: An Engineer’s Approach to Build System Innovation](https://medium.com/ekino-france/rspack-an-engineers-approach-to-build-system-innovation-924e57c596a0)
* \[2025-01] [State of Rspack in Angular](https://edbzn.dev/state-of-rspack-in-angular/)
* \[2025-01] [Nx and Angular with Rspack and Module Federation](https://www.angulararchitects.io/en/blog/nx-with-rspack-and-module-federation/)
* \[2024-12] [Rspack with Module federation V2 is the future](https://dev.to/ibrahimshamma99/rspack-with-module-federation-v2-is-the-future-3g89)
* \[2024-09] [A bundler story: migrating from Webpack to Rspack](https://medium.com/alan/a-bundler-story-migrating-from-webpack-to-rspack-f548c62f757d)
* \[2024-09] [Custom chunk optimization, how code splitting works in Rspack/Webpack](https://scriptedalchemy.medium.com/custom-chunk-optimization-how-code-splitting-works-in-rspack-webpack-146a3fa3a39a)
* \[2024-08] [Lessons learned switching to Rspack](https://birtles.blog/2024/08/14/lessons-learned-switching-to-rspack/)
* \[2024-08] [Why Moving to Rspack and How to Use It with Bazel](https://medium.com/@yanirmanor/why-moving-to-rspack-and-how-to-use-it-with-bazel-9f66139fe493)
* \[2024-08] [Module Federation users now have a clear upgrade path](https://medium.com/@gfox1984/module-federation-users-now-have-a-clear-upgrade-path-1701de23f58e)
* \[2024-08] [Optimizing SPA load times with async chunks preloading (use Rsbuild)](https://mmazzarolo.com/blog/2024-08-13-async-chunk-preloading-on-load/)
* \[2024-06] [Micro Frontend Setup with Nx, Rspack, Module Federation 2.0 and React](https://medium.com/@soumyanildas/micro-frontend-setup-with-nx-rspack-module-federation-2-0-and-react-698674edb09f)
* \[2024-06] [From Webpack to Rspack: Slashing Build Times Effectively](https://medium.com/panorays-r-d-blog/from-webpack-to-rspack-slashing-build-times-effectively-0674fd3cc284)
* \[2024-02] [Why I'm Bullish on Rspack](https://www.raygesualdo.com/posts/bullish-on-rspack/)
* \[2024-02] [Rsdoctor: A Bundle Analysis Solution](https://scriptedalchemy.medium.com/rsdoctor-a-bundle-analysis-solution-ee3f720e0347)
* \[2024-02] [Microfrontends with Module Federation and Rspack — Simple example](https://medium.com/@alexefimenko/microfrontends-with-module-federation-and-rspack-simple-example-730f4e6308a7)
* \[2024-02] [Bun, Biome/OXC, AI Tools and Rsbuild](https://onwebfocus.com/bun)
* \[2024-01] [How I migrated from CRA to Rsbuild](https://dev.to/verthon/how-i-migrated-from-cra-to-rsbuild-4ia8)
* \[2024-01] [Module Federation gets upgraded, and Rspack supports it](https://scriptedalchemy.medium.com/emodule-federation-gets-upgraded-and-rspack-supports-it-5ddb0d1e9546)
* \[2023-10] [Why you should migrate to Rspack from webpack](https://blog.logrocket.com/migrate-rspack-webpack/)
* \[2023-08] [Rust Port of Webpack? Rspack, the New Kid on the Block](https://blog.stackademic.com/rust-port-of-webpack-rspack-the-new-kid-on-the-block-c3a3de569bfb)
* \[2023-04] [What is Rspack? And how does it compare to Webpack in under 5 minutes?](https://www.hamzak.xyz/blog-posts/what-is-rspack-and-how-does-it-compare-to-webpack)
* \[2023-03] [Rspack — Getting up to speed with Nx](https://blog.nrwl.io/rspack-getting-up-to-speed-with-nx-4c34540bccf2)

Chinese blogs (中文):

* \[2025-04] [从 Vite 到 Rsbuild：一次意想不到的构建性能飞跃](https://juejin.cn/post/7496345478658637865)
* \[2024-10] [我把大型团队项目从 Vite 前端迁移到了 Rsbuild，收益如何？](https://juejin.cn/post/7425804396292325414)
* \[2024-09] [\[译\] 一个关于打包工具的故事：从 webpack 迁移到 Rspack](https://juejin.cn/post/7425598941859676170)
* \[2024-08] [开发体验的彻底提升，从 Vite 迁移到 Rspack](https://moonvy.com/blog/post/2024/migrate-vite-to-rsbuild/)
* \[2024-08] [译：前 Firefox 工程师迁移到 Rspack 的经验教训](https://juejin.cn/post/7402554147276980224)
* \[2024-07] [基于 Rspack 实现大仓应用构建提效实践](https://juejin.cn/post/7389925302020014118)

Japanese blogs (日本語):

* \[2025-11] [KARTEの分析システムのレガシーな開発環境を高速にする。pnpm, Rspackの導入で改善できたこと。](https://tech.plaid.co.jp/speedup-pnpm-rspack)
* \[2025-08] [Rails アプリケーションのフロントエンドを webpack から Rspack に移行しました](https://tech.synchro-food.co.jp/entry/2025/08/18/180000)
* \[2025-04] [Rspack に移行したらフロントエンドのビルドがめっちゃ速くなりました](https://buildersbox.corp-sansan.com/entry/2025/04/14/110000)
* \[2026-05] [Rsbuildで組むVueのVRMコンポーネント。ライセンスと配信の安全性を追求したライブラリ設計](https://qiita.com/logue/items/21bb239fed2c4f4a3b2f)
* \[2026-05] [なぜRsbuildスタックなのか？](https://qiita.com/logue/items/e191ed56e922b33e4c8f)

French blogs (Français):

* \[2025-04] [Mon voyage depuis Webpack vers Vite et finalement Rsbuild](https://www.ginkonote.com/fr/utilisateurs/flo/articles/mon-voyage-depuis-webpack-vers-vite-et-finalement-rsbuild@javascript)

## Videos

* \[2025-04]: [Zack Jackson - ByteDance, rspack, and the Future of Web Development](https://www.youtube.com/watch?v=Uo1Gf_32MK0)
* \[2025-04]: [It’s Not Out Yet… But Rstest Has Me HYPED](https://www.youtube.com/watch?v=nhSCmYJew-M)
* \[2025-01]: [Let’s Learn Rsbuild and Rspack](https://www.youtube.com/watch?v=wJ3abFp701k)
* \[2025-01]: [Micro-Frontends in React-Native! Game Changer for Mobile Apps](https://www.youtube.com/watch?v=Lp-5wSsd5Do)
* \[2024-11]: [Everything You Ever Wanted To Know About Web Bundlers (and Rspack!)](https://www.youtube.com/watch?v=ma_c6UNHddI)
* \[2024-07]: [The First Real Webpack Alternative (Written in Rust!)](https://www.youtube.com/watch?v=Vn2Rq2uktLE\&t=37s)
* \[2024-07]: [Microfrontends with Module Federation, Rspack, React and Bit](https://www.youtube.com/watch?v=4CQEPBLxU_g\&t=13s)
* \[2024-06]: [Rsbuild is 3x faster than Vite](https://www.youtube.com/watch?v=w8mL_HiN9Qo\&t=3s)
* \[2024-02]: [Mastering Micro-Frontends With Rspack and Module Federation](https://www.youtube.com/watch?v=32_EikGKESk)
* \[2024-01]: [Micro Frontends - Rspack and Module Federation v1.5](https://www.youtube.com/watch?v=_HWWaPk1vRE\&t=4s)
* \[2023-03]: [Rspack! The Successor of Webpack?](https://www.youtube.com/watch?v=jGTE7xAcg24)

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Web Infra](https://github.com/web-infra-dev) has waived all copyright and related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-23._
