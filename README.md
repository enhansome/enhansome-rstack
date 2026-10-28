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
* [Rstest Utilities](#rstest-utilities)
* [Deployment](#deployment)
* [Libraries](#libraries)
* [Blogs](#blogs)
* [License](#license)

## Resources

### Rstack

Rstack is a unified JavaScript toolchain built around Rspack, with high performance and consistent architecture.

| Name                                                                                                     | Description              | Version                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------- | ------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Rspack](https://github.com/web-infra-dev/rspack) ⭐ 12,960 \| 🐛 239 \| 🌐 Rust \| 📅 2026-10-28         | Bundler                  | <a href="https://npmjs.com/package/@rspack/core"><img src="https://img.shields.io/npm/v/@rspack/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rsbuild](https://github.com/web-infra-dev/rsbuild) ⭐ 3,410 \| 🐛 24 \| 🌐 TypeScript \| 📅 2026-10-28   | Build tool               | <a href="https://npmjs.com/package/@rsbuild/core"><img src="https://img.shields.io/npm/v/@rsbuild/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rslib](https://github.com/web-infra-dev/rslib) ⭐ 1,043 \| 🐛 32 \| 🌐 TypeScript \| 📅 2026-10-28       | Library development tool | <a href="https://npmjs.com/package/@rslib/core"><img src="https://img.shields.io/npm/v/@rslib/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>       |
| [Rspress](https://github.com/web-infra-dev/rspress) ⭐ 2,350 \| 🐛 64 \| 🌐 TypeScript \| 📅 2026-10-28   | Static site generator    | <a href="https://npmjs.com/package/@rspress/core"><img src="https://img.shields.io/npm/v/@rspress/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rsdoctor](https://github.com/web-infra-dev/rsdoctor) ⭐ 1,151 \| 🐛 17 \| 🌐 TypeScript \| 📅 2026-10-26 | Build analyzer           | <a href="https://npmjs.com/package/@rsdoctor/core"><img src="https://img.shields.io/npm/v/@rsdoctor/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a> |
| [Rstest](https://github.com/web-infra-dev/rstest) ⭐ 512 \| 🐛 33 \| 🌐 TypeScript \| 📅 2026-10-28       | Testing framework        | <a href="https://npmjs.com/package/@rstest/core"><img src="https://img.shields.io/npm/v/@rstest/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rslint](https://github.com/web-infra-dev/rslint) ⭐ 462 \| 🐛 46 \| 🌐 Go \| 📅 2026-10-28               | Linter                   | <a href="https://npmjs.com/package/@rslint/core"><img src="https://img.shields.io/npm/v/@rslint/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rstack CLI](https://github.com/rstackjs/rstack-cli) ⭐ 32 \| 🐛 3 \| 🌐 TypeScript \| 📅 2026-10-27      | Unified CLI              | <a href="https://npmjs.com/package/rstack"><img src="https://img.shields.io/npm/v/rstack?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>                 |

### Official Resources

* [rstack-examples](https://github.com/rstackjs/rstack-examples) ⭐ 169 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-13: Examples for Rstack.
* [rspack-binding-template](https://github.com/rstackjs/rspack-binding-template) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2026-10-16: A template for creating custom Rspack bindings with plugins and loaders written in Rust.
* [rstack-design-resources](https://github.com/rstackjs/rstack-design-resources) ⭐ 18 | 🐛 1 | 📅 2026-10-17: Design resources for Rstack.
* [rsdoctor-action](https://github.com/web-infra-dev/rsdoctor-action) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-21: A GitHub Action for bundle size comparisons and pull request reports powered by Rsdoctor.
* [rstack-editor](https://github.com/rstackjs/rstack-editor) ⭐ 12 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-28: Unified VS Code extension for Rstack.

### Ecosystem

Upper-level frameworks or libraries that are powered by Rspack or connected to Rspack:

* [Meteor](https://github.com/meteor/meteor) ⭐ 44,795 | 🐛 355 | 🌐 JavaScript | 📅 2026-10-28: An ultra-simple environment for building modern web applications with Rspack.
* [Extension.js](https://github.com/extension-js/extension.js) ⭐ 5,202 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-28: Create, develop, build, and preview browser extensions for Chrome, Firefox, and Edge with Rspack.
* [Re.Pack](https://github.com/callstack/repack) ⭐ 1,947 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-27: A toolkit to build your React Native application with Rspack.
* [xmcp](https://github.com/basementstudio/xmcp) ⭐ 1,345 | 🐛 19 | 🌐 TypeScript | 📅 2026-10-27: A framework for building and shipping MCP servers with TypeScript and Rspack.
* [Esmx](https://github.com/esmnext/esmx) ⭐ 680 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-13: Esmx is a next-generation micro-frontend framework based on native ESM, with no sandbox or runtime overhead, supporting multi-framework hybrid development and providing high-performance server-side rendering capabilities.
* [The Boring JavaScript Stack](https://github.com/sailscastshq/boring-stack) ⭐ 504 | 🐛 7 | 🌐 JavaScript | 📅 2026-10-26: An opinionated full-stack JavaScript starter built with Sails.js, Inertia.js, and Rsbuild-powered frontend assets.
* [Shakapacker](https://github.com/shakacode/shakapacker) ⭐ 489 | 🐛 15 | 🌐 Ruby | 📅 2026-10-21: Make it easy to use the JavaScript pre-processor and Rspack to manage frontend JavaScript in Rails.
* [storybook-rsbuild](https://github.com/rstackjs/storybook-rsbuild) ⭐ 157 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-26: Storybook builder powered by Rsbuild.
* [Addfox](https://github.com/addfox/addfox) ⭐ 125 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02: A browser extension framework built on Rsbuild.
* [Rshono](https://github.com/rshono/rshono) ⭐ 124 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-27: Minimalist web framework based on Hono, Rspack and React Server Components.
* [Kmi](https://github.com/kmijs/kmi) ⭐ 111 | 🐛 13 | 🌐 JavaScript | 📅 2026-05-15: Based on Umi to provide Rspack support and other best practices.
* [Symfony Reprise](https://github.com/symfony/reprise) ⭐ 87 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-23: Integrates Rsbuild with Symfony.
* [pareto](https://github.com/childrentime/pareto) ⭐ 73 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-06: A lightweight SSR framework centered on stream rendering.
* [Gemkit](https://github.com/mantou132/gem/tree/main/packages/gemkit) ⭐ 54 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-28: A Web Components application framework built on Rsbuild, with file-based routing, layouts, server data and actions, SSR, SSG, ISR and i18n.
* [electron-rsbuild](https://github.com/electron-rsbuild/electron-rsbuild) ⭐ 38 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-27: The Rsbuild-based electron build tool.
* [PrevelteKit](https://github.com/tbocek/preveltekit) ⭐ 38 | 🐛 1 | 🌐 Go | 📅 2026-04-16: A lightweight, high-performance web application framework built on Svelte 5, featuring Server-Side Pre Rendering (SSPR) using Rsbuild as the build tool.
* [effective-rsc](https://github.com/nikhilsnayak/effective-rsc) ⭐ 37 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-19: An Effect-native React Server Components framework for Bun, built on Rspack's native RSC support.
* [serverless-rspack](https://github.com/kitchenshelf/serverless-rspack) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-20: A Serverless framework plugin for zero-config JavaScript and TypeScript code bundling using the high performance Rust-based JavaScript bundler rspack.
* [AUmi](https://github.com/atom-yang/aumi) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-29: Use Rsbuild as Umi's bundler instead of Webpack, get high performance of Rsbuild and all Umi ecosystem.
* [Rselectron](https://github.com/guangzan/rselectron) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-10: An Rsbuild-first Electron development and build tool.
* [@nx/rsbuild](https://nx.dev/nx-api/rsbuild): The Nx plugin for Rsbuild.
* [@nx/rspack](https://nx.dev/nx-api/rspack): The Nx plugin for Rspack.
* [Angular Rspack](https://www.npmjs.com/package/@nx/angular-rspack): Rspack plugin, Rsbuild plugin and tooling for Angular applications.
* [cypress-rspack-dev-server](https://www.npmjs.com/package/cypress-rspack-dev-server): Cypress Component-testing with Rust-based web bundler Rspack's dev server.
* [Docusaurus](https://docusaurus.io/blog/releases/3.6#docusaurus-faster): Help you ship a beautiful documentation site in no time.
* [EMP 3.0](https://empjs.dev/): A high-performance enterprise-level front-end build system built on the Rust ecosystem.
* [Modern.js](https://modernjs.dev/): A progressive React framework for web development.
* [next-rspack](https://rspack.rs/guide/integrations/next): Use Rspack as the bundler for Next.js.
* [Nuxt](https://nuxt.com/): An intuitive Vue framework for creating web applications and websites with Vue.js. Install [@nuxt/rspack-builder](https://www.npmjs.com/package/@nuxt/rspack-builder) to use Rspack as the bundler for Nuxt.
* [Rspeedy](https://lynxjs.org/rspeedy/): The Rspack-based build tool designed specifically for [Lynx](https://lynxjs.org/) applications.
* [TanStack Start](https://tanstack.com/start/latest): Full-stack Framework powered by TanStack Router for React and Solid.

## Skills

* [agent-skills](https://github.com/rstackjs/agent-skills) ⭐ 97 | 🐛 7 | 🌐 JavaScript | 📅 2026-10-22: A collection of Agent Skills for Rstack.

## Starter

### Rspack Starter

* [vue-admin-better](https://github.com/zxwk1998/vue-admin-better) ⭐ 18,935 | 🐛 18 | 🌐 Vue | 📅 2026-10-20: A Vue 3 admin based on Rspack.
* [ng-rspack](https://github.com/edbzn/ng-rspack) ⭐ 37 | 🐛 0 | 🌐 JavaScript | 📅 2024-07-10: Angular + Rspack + Nx + Module Federation 2.0.
* [electron-react-rspack](https://github.com/RyanProMax/electron-react-rspack) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-24: An Electron boilerplate including TypeScript, React, Rspack and ESLint.
* [nuxt-rspack-starter](https://github.com/danielroe/nuxt-rspack-starter) ⭐ 17 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-22: Nuxt starter with Rspack.
* [shark](https://github.com/h7ml/shark) ⭐ 13 | 🐛 8 | 🌐 TypeScript | 📅 2026-02-12: A React project with Rspack, Ant Design, Ant Design Pro Components, Antd\@5 React\@18 AntV G2Plot, ahooks, react-use, Axios, i18next, localforage, Mock.js, NProgress, and more.
* [electron-forge-rspack-template](https://github.com/noshower/electron-forge-rspack-template) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-03
* [r2h](https://github.com/bdxygy/r2h) ⭐ 11 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-22: A blazing-fast SSR starter powered by React 19, Rspack, and Hono.
* [rspack for create-react-app](https://github.com/yanhaijing/rspack-cra) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2023-12-01
* [electron-react-boilerplate](https://github.com/Sovea/electron-react-boilerplate) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-11: An Electron starter with React, TypeScript, and a choice of Rspack or Vite.
* [rspack-react-router-starter](https://github.com/ulivz/rspack-react-router-starter) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2023-11-23

### Rsbuild Starter

* [rsbuild-plugin-template](https://github.com/rstackjs/rsbuild-plugin-template) ⭐ 29 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-14: Use this template to create your own Rsbuild plugin.
* [ding-dong](https://github.com/buildbysarthak/ding-dong) ⭐ 18 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-21: A lightning-fast, modern React template supercharged with Rsbuild.
* [rsbuild-chrome-extension-boilerplate-react](https://github.com/filc-dev/rsbuild-chrome-extension-boilerplate-react) ⚠️ Archived: Chrome extension boilerplate for Rsbuild.
* [react-antd-admin-pro](https://github.com/cl1107/react-antd-admin-pro) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2025-01-14: An admin project template for React. It's built with Rsbuild, React 18, TypeScript 5, antd 5, and React Router.
* [react-tailwind-rsbuild-boilerplate](https://github.com/alonronin/react-tailwind-rsbuild-boilerplate) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2024-07-25: React + React Router + Tailwind CSS with Rsbuild boilerplate.
* [TanStacked](https://github.com/mohmmedraad/TanStacked) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-04-27: React + Tanstack Router + Shadcn + Tailwind CSS v4 And Biome with Rsbuild boilerplate.
* [rsbuild-turborepo-react-module-federation](https://github.com/nguyenbatranvan/rspack-turbo-module-federation) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-19: Rsbuild + Turborepo + Biome + Zustand + React for module federation.
* [rsbuild\_vue3\_h5\_template](https://github.com/DMaiGit/rsbuild_vue3_h5_template) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2024-03-08: A project template for Vue 3. It includes popular libraries such as Axios, Pinia, Vant, and Vue Router.
* [template-rsbuild-react-ts-tailwind](https://github.com/RoyRao2333/template-rsbuild-react-ts-tailwind) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-02-21: Rsbuild starter template with React + Typescript + TailwindCSS + Biome.
* [@trapar-waves/react-antd-pro](https://github.com/Trapar-waves/react-antd-pro) ⭐ 4 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-28: A React-based project leveraging Ant Design Pro, TanStack tools, and Rsbuild.
* [@trapar-waves/react-tanstack](https://github.com/Trapar-waves/react-tanstack) ⭐ 4 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-28: A React template leveraging TanStack tools, with TypeScript, Tailwind CSS, and Rsbuild integration.
* [@trapar-waves/vue-tailwind](https://github.com/Trapar-waves/vue-tailwind) ⭐ 3 | 🐛 3 | 🌐 Vue | 📅 2026-10-28: A Vue 3 project with Tailwind CSS, Rsbuild and modern development tools.
* [umi-rsbuild](https://github.com/atom-yang/aumi-example) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-13: `Umi` + `Rsbuild`, A `Umi` project integrated with `Rsbuild`, you can use `Umi` and its plugins with the same experiences as `Umi` + `Webpack` are.
* [@trapar-waves/react-mantine-tailwind](https://github.com/Trapar-waves/react-mantine-tailwind) ⭐ 2 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-28: A React template integrating Mantine UI and Tailwind CSS for modern web development.
* [react-nestjs-ssr-starter](https://github.com/pikadun/react-nestjs-ssr-starter) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-27: A lightweight full-stack starter for server-side rendering with NestJS and React.
* [rsbuild-vue-starter](https://github.com/logue/rsbuild-vue-starter) ⭐ 2 | 🐛 0 | 🌐 Vue | 📅 2026-10-23: A simple starter template using the Vue + Vue-router + Pinia stack. Includes built-in formatting with rslint and testing with rstest.
* [vue-nestjs-ssr-starter](https://github.com/pikadun/vue-nestjs-ssr-starter) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-12: A lightweight full-stack SSR starter with Vue 3, NestJS, Fastify, PrimeVue, and Rsbuild.
* [@trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind) ⭐ 0 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-28: A modern UI development template integrating React and Tailwind CSS, with Rsbuild, TypeScript, ESLint.

### Rslib Starter

* [ts-lib-starter](https://github.com/ulivz/ts-lib-starter) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-07: A hassle-free TS library template, powered by Rslib.
* [rslib-npm-template](https://github.com/LLmoskk/rslib-npm-template) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-07: A starter template for developing React components with Rslib, featuring automated versioning and publishing using semantic-release.
* [@trapar-waves/llm-template](https://github.com/Trapar-waves/llm-template) ⭐ 3 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-28: A template for LLM development integrating AI tools, TypeScript, Zod, and Rslib.
* [rstack-library-starter](https://github.com/logue/rstack-library-starter) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-25: Production-ready starter for Rsbuild/Rslib library development. Built on Rstack (Rspack, Rslib, Rstest, Rslint), with structured documentation patterns (AGENTS.md, PLAN.md), comprehensive testing, and a minimal Pico.css demo site. Validated across multiple libraries.

## Plugins

### Rspack Plugins

* [@unocss/webpack](https://github.com/unocss/unocss/tree/main/packages-integrations/webpack) ⭐ 18,988 | 🐛 116 | 🌐 TypeScript | 📅 2026-10-26: Plugin for UnoCSS.
* [webpack-bundle-analyzer](https://github.com/webpack/webpack-bundle-analyzer) ⭐ 12,655 | 🐛 22 | 🌐 JavaScript | 📅 2026-10-27: Visualize size of webpack output files with an interactive zoomable treemap.
* [@vanilla-extract/webpack-plugin](https://github.com/vanilla-extract-css/vanilla-extract) ⭐ 10,441 | 🐛 78 | 🌐 TypeScript | 📅 2026-10-08: Integrating vanilla-extract with webpack / Rspack.
* [code-inspector-plugin](https://github.com/zh-lx/code-inspector) ⭐ 3,049 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-13: Click an element on the page, it can automatically open the editor and position the cursor to the source code of the element.
* [@module-federation/enhanced](https://github.com/module-federation/core/tree/main/packages/enhanced) ⭐ 2,672 | 🐛 121 | 🌐 JavaScript | 📅 2026-10-28: Provides enhanced features for Module Federation.
* [webpackbar](https://github.com/unjs/webpackbar) ⭐ 2,095 | 🐛 29 | 🌐 TypeScript | 📅 2026-10-28: Elegant ProgressBar and Profiler for Rspack.
* [clean-webpack-plugin](https://github.com/johnagan/clean-webpack-plugin) ⚠️ Archived: Remove your build folder before building.
* [@serwist/webpack-plugin](https://github.com/serwist/serwist) ⭐ 1,498 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-04: generate a manifest of local files for progressive web apps.
* [compression-webpack-plugin](https://github.com/webpack/compression-webpack-plugin) ⚠️ Archived: Prepare compressed versions of assets to serve them with Content-Encoding.
* [dotenv-webpack](https://github.com/mrsteele/dotenv-webpack) ⭐ 1,295 | 🐛 20 | 🌐 JavaScript | 📅 2026-03-07: A secure plugin that supports dotenv and other environment variables.
* [@rsdoctor/rspack-plugin](https://github.com/web-infra-dev/rsdoctor) ⭐ 1,151 | 🐛 17 | 🌐 TypeScript | 📅 2026-10-26: An Rspack plugin for integrating Rsdoctor.
* [sonda](https://github.com/filipsobol/sonda) ⭐ 790 | 🐛 15 | 🌐 TypeScript | 📅 2026-09-28: Visualizer and analyzer for JavaScript and CSS bundles.
* [case-sensitive-paths-webpack-plugin](https://github.com/Urthen/case-sensitive-paths-webpack-plugin) ⭐ 428 | 🐛 43 | 🌐 JavaScript | 📅 2023-01-07: Enforces case sensitive paths of all required modules.
* [css-minimizer-webpack-plugin](https://github.com/webpack/css-minimizer-webpack-plugin) ⚠️ Archived: Uses cssnano to optimize and minify your CSS.
* [node-polyfill-webpack-plugin](https://github.com/Richienb/node-polyfill-webpack-plugin) ⭐ 301 | 🐛 14 | 🌐 JavaScript | 📅 2024-12-04: Polyfill Node.js core modules.
* [@lunora/rspack](https://github.com/anolilab/lunora/tree/alpha/packages/rspack) ⭐ 292 | 🐛 35 | 🌐 TypeScript | 📅 2026-10-28: Rspack and Rsbuild integration for the Lunora realtime backend framework on Cloudflare Workers.
* [@sentry/webpack-plugin](https://github.com/getsentry/sentry-javascript-bundler-plugins) ⭐ 177 | 🐛 22 | 🌐 TypeScript | 📅 2026-10-27: Provides source map and release management support for Sentry.
* [@datadog/rspack-plugin](https://github.com/DataDog/build-plugins) ⭐ 111 | 🐛 55 | 🌐 TypeScript | 📅 2026-10-28: A Rspack plugin to interact with Datadog from your builds.
* [rspack-plugin-virtual-module](https://github.com/rstackjs/rspack-plugin-virtual-module) ⚠️ Archived: An Rspack plugin that allows you to create virtual modules.
* [ide-byebye](https://github.com/bo-516/ide-byebye) ⭐ 30 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-20: Rspack and Rsbuild plugin to click an element on the page, describe the change, and send its source location to AI coding agents such as Claude Code, Codex and Cursor.
* [@aaroon/workbox-rspack-plugin](https://github.com/Clarkkkk/workbox-rspack-plugin) ⭐ 28 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-23: A plugin to use workbox in Rspack.
* [ts-checker-rspack-plugin](https://github.com/rstackjs/ts-checker-rspack-plugin) ⭐ 28 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-26: Runs TypeScript type checker on a separate process.
* [@rspack/plugin-react-refresh](https://github.com/rstackjs/rspack-plugin-react-refresh) ⭐ 20 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-14: Support React Fast Refresh.
* [html-rspack-plugin](https://github.com/rstackjs/html-rspack-plugin) ⭐ 19 | 🐛 5 | 🌐 JavaScript | 📅 2026-10-15: Generate files to serve your Rspack bundles.
* [rspack-manifest-plugin](https://github.com/rstackjs/rspack-manifest-plugin) ⭐ 19 | 🐛 2 | 🌐 JavaScript | 📅 2026-10-22: An Rspack plugin for generating an asset manifest.
* [@vue-devtools-rstack/rspack](https://github.com/OskarLebuda/vue-devtools-rstack/tree/main/packages/rspack) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-23: Integrates Vue DevTools with raw Rspack setups, with feature parity with `vite-plugin-vue-devtools`.
* [rspack-plugin-mock](https://github.com/pengzhanbo/rspack-plugin-mock) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-10: Rspack and Rsbuild plugin for API mock dev server.
* [rspack-plugin-retry-chunk-load](https://github.com/khodorammar/rspack-plugin-retry-chunk-load) ⭐ 11 | 🐛 3 | 🌐 TypeScript | 📅 2025-09-14 Retry loading of chunks that failed to load.
* [rspack-deno-plugin](https://github.com/LonelySnowman/rspack-deno-plugin) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-18: Make Rspack run correctly in the deno environment.
* [@rspack/plugin-preact-refresh](https://github.com/rstackjs/rspack-plugin-preact-refresh) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-26: Support Preact Refresh.
* [eslint-rspack-plugin](https://github.com/rstackjs/eslint-rspack-plugin) ⭐ 9 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-15: Rspack plugin to run ESLint checks during the compilation.
* [typia-rspack-plugin](https://github.com/colinaaa/typia-rspack-plugin) ⭐ 8 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-27: A Rspack plugin for `typia` - TypeScript transformer for runtime type checking and validation.
* [react-cosmos-plugin-rspack](https://github.com/birchill/react-cosmos-plugin-rspack/) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-10: Allows building / running React Cosmos using Rspack.
* [inject-manifest-plugin](https://github.com/tobua/inject-manifest-plugin) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2024-06-18: Injects a Workbox PWA manifest into a Service Worker.
* [rspack-circular-dependency-plugin](https://github.com/Sunny-117/rspack-circular-dependency-plugin) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-02-19: Detect circular dependencies in modules compiled with Rspack.
* [rspack-plugin-cli-copy](https://github.com/rstackjs/rspack-plugin-cli-copy) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20: Start the project and automatically copy the network URL of the terminal.
* [rspack-s3-plugin](https://github.com/ts-codeworks/rspack-s3-plugin) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-11-25: A Rspack plugin for uploading compiled assets to Amazon S3 after build.
* [@golar-rstack/rspack](https://github.com/OskarLebuda/golar-rstack-plugin/tree/main/packages/rspack) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-28: Runs golar type checking and type-aware linting in a separate process as an Rspack plugin.
* [@heyq02/rspack-plugin-git-revision](https://github.com/heyq02/rspack-plugin-git-revision) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-13: Rspack and Rsbuild plugin for generating version, commit hash, branch, and last commit time metadata from Git.
* [compression-rspack-plugin](https://github.com/ramon-villain/compression-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-30: Rust-native parallel compression plugin for Rspack. Drop-in replacement for compression-webpack-plugin with gzip, brotli, deflate, and deflateRaw — all parallelized across CPU cores via Rust + rayon.
* [html-inline-css-rspack-plugin](https://github.com/cbbfcd/html-inline-css-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2024-11-20 A Rspack plugin to convert external stylesheets into embedded stylesheets.
* [html-rspack-skip-assets-plugin](https://github.com/cbbfcd/html-rspack-skip-assets-plugin) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-20 Adapt `html-webpack-skip-assets-plugin` to Rspack.
* [rtlcss-rspack-plugin](https://github.com/cbbfcd/rtlcss-rspack-plugin) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2024-11-20: Rspack plugin to create a second css bundle, processed to be rtl.
* [oxc-webpack-plugin](https://github.com/oxc-project/oxc-webpack-plugin) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-27: Minify JavaScript assets using Oxc.
* [rspack-plugin-solid-svg](https://github.com/solarlime/rspack-plugin-solid-svg) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-07-14: Rspack plugin for transforming SVG files into SolidJS components.
* [rspack-unocss-plugin](https://github.com/umbrella22/rspack-unocss-plugin) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-20: Native UnoCSS integration for Rspack with virtual CSS modules and native CSS processing.
* [@nx/module-federation](https://nx.dev/docs/kb/nx-module-federation-plugin): Includes several Rspack plugins for Nx and Module Federation.
* [@octanejs/rspack-plugin](https://octanejs.dev/docs/build-tools#rspack): Rspack loader and compiler plugin for Octane TSRX source.
* [rspack-plugin-svg-sprite](https://www.npmjs.com/package/rspack-plugin-svg-sprite): SVG sprite plugin for Rspack — drop-in replacement for svg-sprite-loader.
* [zephyr-rspack-plugin](https://www.npmjs.com/package/zephyr-rspack-plugin): An Rspack plugin for deploying applications with Zephyr Cloud.

### Rspack Loaders

Rspack and Rsbuild support most of the webpack loaders, such as:

* [@tailwindcss/webpack](https://github.com/tailwindlabs/tailwindcss/tree/main/packages/%40tailwindcss-webpack) ⭐ 98,006 | 🐛 105 | 🌐 TypeScript | 📅 2026-10-19: A webpack loader for Tailwind CSS v4.
* [@mdx-js/loader](https://github.com/mdx-js/mdx/tree/main/packages/loader) ⭐ 19,835 | 🐛 21 | 🌐 JavaScript | 📅 2026-10-26: Loader for MDX.
* [@svgr/webpack](https://github.com/gregberge/svgr/tree/main/packages/webpack) ⭐ 11,060 | 🐛 151 | 🌐 TypeScript | 📅 2026-03-01: Loader for SVGR.
* [babel-loader](https://github.com/babel/babel-loader) ⭐ 4,835 | 🐛 67 | 🌐 JavaScript | 📅 2026-09-03: Transpiling JavaScript files using Babel.
* [css-loader](https://github.com/webpack/css-loader) ⚠️ Archived: Interprets @import and url() in CSS files and resolve them.
* [sass-loader](https://github.com/webpack/sass-loader) ⭐ 3,889 | 🐛 9 | 🌐 JavaScript | 📅 2026-10-27: Compiles Sass/SCSS files to CSS.
* [postcss-loader](https://github.com/webpack/postcss-loader) ⭐ 2,839 | 🐛 15 | 🌐 JavaScript | 📅 2026-10-18: Loader to process CSS with PostCSS.
* [style-loader](https://github.com/webpack/style-loader) ⚠️ Archived: Inject CSS into the DOM.
* [@vue-vine/rspack-loader](https://github.com/vue-vine/vue-vine) ⭐ 1,441 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-24: Rspack loader for Vue Vine.
* [less-loader](https://github.com/webpack/less-loader) ⭐ 960 | 🐛 10 | 🌐 JavaScript | 📅 2026-10-27: Compiles Less to CSS.
* [svelte-loader](https://github.com/sveltejs/svelte-loader) ⭐ 604 | 🐛 22 | 🌐 JavaScript | 📅 2026-04-02: Loader for svelte components.
* [svg-react-loader](https://github.com/jhamlet/svg-react-loader) ⚠️ Archived: Turn SVGs into React Components.
* [stylus-loader](https://github.com/webpack/stylus-loader) ⭐ 493 | 🐛 6 | 🌐 JavaScript | 📅 2026-10-27: Compiles Stylus to CSS.
* [source-map-loader](https://github.com/webpack-contrib/source-map-loader) ⚠️ Archived: Extracts source maps from existing source files.
* [svgo-loader](https://github.com/svg/svgo-loader) ⭐ 309 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-26: Loader for SVGO.
* [yaml-loader](https://github.com/eemeli/yaml-loader) ⭐ 153 | 🐛 7 | 🌐 JavaScript | 📅 2026-05-22: Allows importing YAML files as JS objects.
* [react-compiler-webpack](https://github.com/SukkaW/react-compiler-webpack) ⭐ 123 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-05: The webpack / Rspack loader for React Compiler.
* [rsbuild-plugin-markdown-loader](https://github.com/aliezzahn/rsbuild-plugin-markdown-loader) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-20: Importing and rendering Markdown files as React components or pure HTML.
* [oxc-webpack-loader](https://github.com/oxc-project/oxc-webpack-loader) ⭐ 18 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-27: Uses Oxc for fast JavaScript and TypeScript transformation.
* [rspack-vue-loader](https://github.com/rstackjs/rspack-vue-loader) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-25: Vue loader for Rspack.
* [worker-rspack-loader](https://github.com/rstackjs/worker-rspack-loader) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2026-09-08: An Rspack loader that registers a script as a Web Worker.
* [coffee-loader](https://www.npmjs.com/package/coffee-loader): Compile CoffeeScript to JavaScript.
* [html-loader](https://www.npmjs.com/package/html-loader): Exports HTML as string.
* [imports-loader](https://www.npmjs.com/package/imports-loader): Use modules that depend on specific global variables.
* [node-loader](https://www.npmjs.com/package/node-loader): Allows to connect native node modules with .node extension.

### Rsbuild Plugins

See the [Rsbuild plugin list](https://rsbuild.rs/plugins/list) for official and community plugins.

### Rspress Plugins

* [Community plugins](https://rspress.rs/plugin/community-plugins/overview)
* [Official plugins](https://rspress.rs/plugin/official-plugins/overview)

### Unplugin

Rspack and Rsbuild support most of the [unplugin](https://github.com/unplugin), such as:

* [unplugin-icons](https://github.com/unplugin/unplugin-icons) ⭐ 4,960 | 🐛 88 | 🌐 TypeScript | 📅 2026-09-11: Access thousands of icons as components on-demand universally.
* [unplugin-vue-components](https://github.com/unplugin/unplugin-vue-components) ⭐ 4,294 | 🐛 146 | 🌐 TypeScript | 📅 2026-05-20: On-demand components auto importing for Vue.
* [unplugin-auto-import](https://github.com/unplugin/unplugin-auto-import) ⭐ 3,799 | 🐛 72 | 🌐 TypeScript | 📅 2026-08-03: Auto import APIs on-demand.
* [unplugin-vue-macros](https://github.com/vue-macros/vue-macros) ⭐ 1,986 | 🐛 38 | 🌐 TypeScript | 📅 2026-10-28: Explore more macros and syntax sugar to Vue.
* [unplugin-dts](https://github.com/qmhc/unplugin-dts) ⭐ 1,531 | 🐛 21 | 🌐 TypeScript | 📅 2026-10-28: An unplugin that generates declaration files (\*.d.ts).
* [zod-compiler](https://github.com/gajus/zod-compiler) ⭐ 819 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-24: Compile Zod schemas into zero-overhead validation functions at build time.
* [unplugin-turbo-console](https://github.com/unplugin/unplugin-turbo-console) ⭐ 712 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-15: Improve the Developer Experience of console.
* [unplugin-macros](https://github.com/unplugin/unplugin-macros) ⭐ 282 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-26: Macros plugin for bundlers.
* [@intlify/unplugin-vue-i18n](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n) ⭐ 269 | 🐛 26 | 🌐 TypeScript | 📅 2026-10-27: unplugin for Vue I18n.
* [unplugin-element-plus](https://github.com/element-plus/unplugin-element-plus) ⭐ 252 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-28: Import Element Plus on demand.
* [unplugin-info](https://github.com/yjl9903/unplugin-info) ⭐ 112 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-26: Export build information as a virtual module.
* [unplugin-ast](https://github.com/unplugin/unplugin-ast) ⭐ 100 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-22: Manipulate the AST to transform your code.
* [unplugin-oxc](https://github.com/unplugin/unplugin-oxc) ⭐ 57 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-26: Transform and minify JavaScript and TypeScript with Oxc.
* [@iconify/unplugin](https://github.com/iconify/iconify-unplugin) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-19: Generate icon components on demand from Iconify.
* [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload) ⭐ 39 | 🐛 2 | 🌐 TypeScript | 📅 2024-12-15: Inject `<link rel="preload">` to your index.html based on your build assets. Need to be used with HTMLWebpackPlugin or HTMLRspackPlugin.
* [unplugin-favicons](https://github.com/anolilab/unplugin-favicons) ⭐ 10 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-27: Generate favicons for your project with caching for blazing fast rebuilds.
* [unplugin-build-info](https://github.com/renzp94/unplugin-build-info) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-05: Print the build information on the console.
* [unplugin-ata](https://github.com/ata-core/unplugin-ata) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-26: Compile JSON Schema files into standalone ata-validator modules with TypeScript declarations at build time.
* [unplugin-build-meta](https://github.com/luxass/unplugin-build-meta) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-28: Import build metadata into your JavaScript/TypeScript projects.
* [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.
* [@formatjs/unplugin](https://www.npmjs.com/package/@formatjs/unplugin): Universal build plugin for FormatJS.
* [@stylexjs/unplugin](https://www.npmjs.com/package/@stylexjs/unplugin): Universal bundler plugin for StyleX.
* [@tanstack/router-plugin](https://www.npmjs.com/package/@tanstack/router-plugin): Automatically generate configuration for TanStack Router.
* [unplugin-vue](https://www.npmjs.com/package/unplugin-vue): Transform Vue 3 SFC to JavaScript.

## Rstest Adapters

* [@modern-js/adapter-rstest](https://github.com/web-infra-dev/modern.js/tree/main/packages/cli/adapter-rstest) ⭐ 5,050 | 🐛 51 | 🌐 TypeScript | 📅 2026-10-28: Rstest adapter for Modern.js configuration.
* [@rstest/adapter-rsbuild](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rsbuild) ⭐ 512 | 🐛 33 | 🌐 TypeScript | 📅 2026-10-28: Rstest adapter for Rsbuild configuration.
* [@rstest/adapter-rslib](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rslib) ⭐ 512 | 🐛 33 | 🌐 TypeScript | 📅 2026-10-28: Rstest adapter for Rslib configuration.
* [@rstest/adapter-rspack](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rspack) ⭐ 512 | 🐛 33 | 🌐 TypeScript | 📅 2026-10-28: Rstest adapter for Rspack configuration.

## Rstest Utilities

* [path-serializer](https://github.com/rstackjs/path-serializer) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-04: A snapshot serializer that normalizes system-specific paths for stable snapshots.
* [effect-rstest](https://github.com/Nsttt/effect-rstest) ⭐ 6 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-22: Effect test helpers for Rstest, with shared layers, test services, and property testing.
* [rstest-fetch-mock](https://github.com/rstackjs/rstest-fetch-mock) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-04: Mock the global fetch API in Rstest tests.
* [rstest-canvas-mock](https://github.com/rstackjs/rstest-canvas-mock) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-08: Mock the Canvas API in Rstest tests.
* [rstest-sonar-reporter](https://github.com/onigoetz/rstest-sonar-reporter) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-26: A Rstest reporter that outputs test results in SonarQube's Generic Test Execution XML format.

## Deployment

* [Zephyr Cloud](https://zephyr-cloud.io): A cloud-agnostic deployment platform offering sub-seconds `deploy from one command` experience.

## Libraries

* [Jetpack](https://github.com/KidkArolis/jetpack) ⭐ 1,307 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-24: Jetpack wraps Rspack to create a smoother developer experience.
* [rspackify](https://github.com/SyMind/rspackify) ⭐ 43 | 🐛 3 | 🌐 TypeScript | 📅 2024-09-04: Experience lightning-fast builds by instantly switching from webpack to Rspack.
* [@rspack/dev-server](https://github.com/rstackjs/rspack-dev-server) ⭐ 42 | 🐛 4 | 🌐 JavaScript | 📅 2026-10-26: Dev server for Rspack, provides the same API as webpack-dev-server.
* [@rspack/resolver](https://github.com/rstackjs/rspack-resolver) ⭐ 42 | 🐛 19 | 🌐 Rust | 📅 2026-09-04: A Rust port of enhanced-resolve.
* [rspack-chain](https://github.com/rstackjs/rspack-chain) ⭐ 35 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-14: A chaining API to generate and simplify the modification of Rspack configurations.
* [@rspack/lite-tapable](https://github.com/rstackjs/rspack-lite-tapable) ⭐ 9 | 🐛 4 | 🌐 JavaScript | 📅 2026-10-14: Lite weight tapable for Rspack.
* [Sails Shipwright](https://github.com/sailshq/sails-hook-shipwright) ⭐ 7 | 🐛 2 | 🌐 JavaScript | 📅 2026-09-09 - The modern asset pipeline for [Sails](https://sailsjs.com) powered by Rsbuild.
* [@rspack/dev-middleware](https://github.com/rstackjs/rspack-dev-middleware) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-10-22: A development middleware for Rspack.
* [rspack-merge](https://github.com/rstackjs/rspack-merge) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-14: Smart configuration merging for Rspack.
* [Spinpack](https://github.com/denniscual/spinpack) ⭐ 1 | 🐛 1 | 🌐 TypeScript | 📅 2024-06-14: A CLI tool that turbocharges the developer server experience for CRA projects with Rspack.

## Blogs

### Rspack Team

Blogs from the Rspack team:

* [rspack.rs/blogs](https://rspack.rs/blog/)
* [web-infra-dev/blogs](https://github.com/web-infra-dev/blogs) ⭐ 38 | 🐛 0 | 📅 2025-09-04

### Community

English blogs:

* \[2026-10] [Publishing a JavaScript Library With Rslib](https://blog.openreplay.com/publish-javascript-library-rslib/)
* \[2026-10] [State of Rspack in Angular: 2026 Update](https://edbzn.dev/blog/state-of-rspack-in-angular-2026/)
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

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-28._
