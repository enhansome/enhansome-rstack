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
| [Rspack](https://github.com/web-infra-dev/rspack) ⭐ 12,961 \| 🐛 251 \| 🌐 Rust \| 📅 2026-10-30         | Bundler                  | <a href="https://npmjs.com/package/@rspack/core"><img src="https://img.shields.io/npm/v/@rspack/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rsbuild](https://github.com/web-infra-dev/rsbuild) ⭐ 3,413 \| 🐛 59 \| 🌐 TypeScript \| 📅 2026-10-30   | Build tool               | <a href="https://npmjs.com/package/@rsbuild/core"><img src="https://img.shields.io/npm/v/@rsbuild/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rslib](https://github.com/web-infra-dev/rslib) ⭐ 1,043 \| 🐛 31 \| 🌐 TypeScript \| 📅 2026-10-29       | Library development tool | <a href="https://npmjs.com/package/@rslib/core"><img src="https://img.shields.io/npm/v/@rslib/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>       |
| [Rspress](https://github.com/web-infra-dev/rspress) ⭐ 2,352 \| 🐛 64 \| 🌐 TypeScript \| 📅 2026-10-30   | Static site generator    | <a href="https://npmjs.com/package/@rspress/core"><img src="https://img.shields.io/npm/v/@rspress/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>   |
| [Rsdoctor](https://github.com/web-infra-dev/rsdoctor) ⭐ 1,150 \| 🐛 20 \| 🌐 TypeScript \| 📅 2026-10-29 | Build analyzer           | <a href="https://npmjs.com/package/@rsdoctor/core"><img src="https://img.shields.io/npm/v/@rsdoctor/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a> |
| [Rstest](https://github.com/web-infra-dev/rstest) ⭐ 513 \| 🐛 30 \| 🌐 TypeScript \| 📅 2026-10-30       | Testing framework        | <a href="https://npmjs.com/package/@rstest/core"><img src="https://img.shields.io/npm/v/@rstest/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rslint](https://github.com/web-infra-dev/rslint) ⭐ 462 \| 🐛 49 \| 🌐 Go \| 📅 2026-10-30               | Linter                   | <a href="https://npmjs.com/package/@rslint/core"><img src="https://img.shields.io/npm/v/@rslint/core?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>     |
| [Rstack CLI](https://github.com/rstackjs/rstack-cli) ⭐ 34 \| 🐛 4 \| 🌐 TypeScript \| 📅 2026-10-30      | Unified CLI              | <a href="https://npmjs.com/package/rstack"><img src="https://img.shields.io/npm/v/rstack?style=flat-square&colorA=564341&colorB=EDED91" alt="npm version" /></a>                 |

### Official Resources

* [rstack-examples](https://github.com/rstackjs/rstack-examples) ⭐ 169 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-13: Examples for Rstack.
* [rspack-binding-template](https://github.com/rstackjs/rspack-binding-template) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2026-10-16: A template for creating custom Rspack bindings with plugins and loaders written in Rust.
* [rstack-design-resources](https://github.com/rstackjs/rstack-design-resources) ⭐ 18 | 🐛 1 | 📅 2026-10-29: Design resources for Rstack.
* [rsdoctor-action](https://github.com/web-infra-dev/rsdoctor-action) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-29: A GitHub Action for bundle size comparisons and pull request reports powered by Rsdoctor.
* [rstack-editor](https://github.com/rstackjs/rstack-editor) ⭐ 12 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-30: Unified VS Code extension for Rstack.

### Ecosystem

Upper-level frameworks or libraries that are powered by Rspack or connected to Rspack:

* [Meteor](https://github.com/meteor/meteor) ⭐ 44,793 | 🐛 357 | 🌐 JavaScript | 📅 2026-10-29: An ultra-simple environment for building modern web applications with Rspack.
* [Extension.js](https://github.com/extension-js/extension.js) ⭐ 5,201 | 🐛 5 | 🌐 TypeScript | 📅 2026-10-30: Create, develop, build, and preview browser extensions for Chrome, Firefox, and Edge with Rspack.
* [Re.Pack](https://github.com/callstack/repack) ⭐ 1,947 | 🐛 26 | 🌐 TypeScript | 📅 2026-10-29: A toolkit to build your React Native application with Rspack.
* [xmcp](https://github.com/basementstudio/xmcp) ⭐ 1,347 | 🐛 20 | 🌐 TypeScript | 📅 2026-10-28: A framework for building and shipping MCP servers with TypeScript and Rspack.
* [Esmx](https://github.com/esmnext/esmx) ⭐ 680 | 🐛 7 | 🌐 TypeScript | 📅 2026-08-13: Esmx is a next-generation micro-frontend framework based on native ESM, with no sandbox or runtime overhead, supporting multi-framework hybrid development and providing high-performance server-side rendering capabilities.
* [The Boring JavaScript Stack](https://github.com/sailscastshq/boring-stack) ⭐ 504 | 🐛 7 | 🌐 JavaScript | 📅 2026-10-26: An opinionated full-stack JavaScript starter built with Sails.js, Inertia.js, and Rsbuild-powered frontend assets.
* [Shakapacker](https://github.com/shakacode/shakapacker) ⭐ 489 | 🐛 15 | 🌐 Ruby | 📅 2026-10-21: Make it easy to use the JavaScript pre-processor and Rspack to manage frontend JavaScript in Rails.
* [storybook-rsbuild](https://github.com/rstackjs/storybook-rsbuild) ⭐ 157 | 🐛 9 | 🌐 TypeScript | 📅 2026-10-26: Storybook builder powered by Rsbuild.
* [Addfox](https://github.com/addfox/addfox) ⭐ 125 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-02: A browser extension framework built on Rsbuild.
* [Rshono](https://github.com/rshono/rshono) ⭐ 125 | 🐛 4 | 🌐 TypeScript | 📅 2026-10-29: Minimalist web framework based on Hono, Rspack and React Server Components.
* [Kmi](https://github.com/kmijs/kmi) ⭐ 111 | 🐛 13 | 🌐 JavaScript | 📅 2026-05-15: Based on Umi to provide Rspack support and other best practices.
* [Symfony Reprise](https://github.com/symfony/reprise) ⭐ 88 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-23: Integrates Rsbuild with Symfony.
* [pareto](https://github.com/childrentime/pareto) ⭐ 73 | 🐛 1 | 🌐 TypeScript | 📅 2026-05-06: A lightweight SSR framework centered on stream rendering.
* [Gemkit](https://github.com/mantou132/gem/tree/main/packages/gemkit) ⭐ 55 | 🐛 6 | 🌐 TypeScript | 📅 2026-10-30: A Web Components application framework built on Rsbuild, with file-based routing, layouts, server data and actions, SSR, SSG, ISR and i18n.
* [PrevelteKit](https://github.com/tbocek/preveltekit) ⭐ 39 | 🐛 1 | 🌐 Go | 📅 2026-10-29: A lightweight, high-performance web application framework built on Svelte 5, featuring Server-Side Pre Rendering (SSPR) using Rsbuild as the build tool.
* [electron-rsbuild](https://github.com/electron-rsbuild/electron-rsbuild) ⭐ 38 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-27: The Rsbuild-based electron build tool.
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

* [vue-admin-better](https://github.com/zxwk1998/vue-admin-better) ⭐ 18,934 | 🐛 18 | 🌐 Vue | 📅 2026-10-20: A Vue 3 admin based on Rspack.
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
* [@trapar-waves/react-antd-pro](https://github.com/Trapar-waves/react-antd-pro) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-30: A React-based project leveraging Ant Design Pro, TanStack tools, and Rsbuild.
* [@trapar-waves/react-tanstack](https://github.com/Trapar-waves/react-tanstack) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-30: A React template leveraging TanStack tools, with TypeScript, Tailwind CSS, and Rsbuild integration.
* [@trapar-waves/vue-tailwind](https://github.com/Trapar-waves/vue-tailwind) ⭐ 3 | 🐛 1 | 🌐 Vue | 📅 2026-10-30: A Vue 3 project with Tailwind CSS, Rsbuild and modern development tools.
* [umi-rsbuild](https://github.com/atom-yang/aumi-example) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-13: `Umi` + `Rsbuild`, A `Umi` project integrated with `Rsbuild`, you can use `Umi` and its plugins with the same experiences as `Umi` + `Webpack` are.
* [@trapar-waves/react-mantine-tailwind](https://github.com/Trapar-waves/react-mantine-tailwind) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-30: A React template integrating Mantine UI and Tailwind CSS for modern web development.
* [react-nestjs-ssr-starter](https://github.com/pikadun/react-nestjs-ssr-starter) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2026-09-27: A lightweight full-stack starter for server-side rendering with NestJS and React.
* [rsbuild-vue-starter](https://github.com/logue/rsbuild-vue-starter) ⭐ 2 | 🐛 0 | 🌐 Vue | 📅 2026-10-23: A simple starter template using the Vue + Vue-router + Pinia stack. Includes built-in formatting with rslint and testing with rstest.
* [vue-nestjs-ssr-starter](https://github.com/pikadun/vue-nestjs-ssr-starter) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2026-03-12: A lightweight full-stack SSR starter with Vue 3, NestJS, Fastify, PrimeVue, and Rsbuild.
* [@trapar-waves/react-tailwind](https://github.com/Trapar-waves/react-tailwind) ⭐ 0 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-30: A modern UI development template integrating React and Tailwind CSS, with Rsbuild, TypeScript, ESLint.

### Rslib Starter

* [ts-lib-starter](https://github.com/ulivz/ts-lib-starter) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-07: A hassle-free TS library template, powered by Rslib.
* [rslib-npm-template](https://github.com/LLmoskk/rslib-npm-template) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-07: A starter template for developing React components with Rslib, featuring automated versioning and publishing using semantic-release.
* [@trapar-waves/llm-template](https://github.com/Trapar-waves/llm-template) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-30: A template for LLM development integrating AI tools, TypeScript, Zod, and Rslib.
* [rstack-library-starter](https://github.com/logue/rstack-library-starter) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-25: Production-ready starter for Rsbuild/Rslib library development. Built on Rstack (Rspack, Rslib, Rstest, Rslint), with structured documentation patterns (AGENTS.md, PLAN.md), comprehensive testing, and a minimal Pico.css demo site. Validated across multiple libraries.

## Plugins

### Rspack Plugins

See the [Rspack community plugin list](https://rspack.rs/guide/start/ecosystem#community-plugins).

### Rspack Loaders

See the [Rspack loader list](https://rspack.rs/guide/start/ecosystem#loaders) for community loaders.

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
* [unplugin-vue-macros](https://github.com/vue-macros/vue-macros) ⭐ 1,986 | 🐛 38 | 🌐 TypeScript | 📅 2026-10-29: Explore more macros and syntax sugar to Vue.
* [unplugin-dts](https://github.com/qmhc/unplugin-dts) ⭐ 1,531 | 🐛 21 | 🌐 TypeScript | 📅 2026-10-29: An unplugin that generates declaration files (\*.d.ts).
* [zod-compiler](https://github.com/gajus/zod-compiler) ⭐ 820 | 🐛 1 | 🌐 TypeScript | 📅 2026-09-24: Compile Zod schemas into zero-overhead validation functions at build time.
* [unplugin-turbo-console](https://github.com/unplugin/unplugin-turbo-console) ⭐ 712 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-15: Improve the Developer Experience of console.
* [unplugin-macros](https://github.com/unplugin/unplugin-macros) ⭐ 283 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-29: Macros plugin for bundlers.
* [@intlify/unplugin-vue-i18n](https://github.com/intlify/bundle-tools/tree/main/packages/unplugin-vue-i18n) ⭐ 269 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-27: unplugin for Vue I18n.
* [unplugin-element-plus](https://github.com/element-plus/unplugin-element-plus) ⭐ 252 | 🐛 13 | 🌐 TypeScript | 📅 2026-10-29: Import Element Plus on demand.
* [unplugin-info](https://github.com/yjl9903/unplugin-info) ⭐ 112 | 🐛 8 | 🌐 TypeScript | 📅 2026-10-29: Export build information as a virtual module.
* [unplugin-ast](https://github.com/unplugin/unplugin-ast) ⭐ 100 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-28: Manipulate the AST to transform your code.
* [unplugin-oxc](https://github.com/unplugin/unplugin-oxc) ⭐ 57 | 🐛 1 | 🌐 TypeScript | 📅 2026-10-26: Transform and minify JavaScript and TypeScript with Oxc.
* [@iconify/unplugin](https://github.com/iconify/iconify-unplugin) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-19: Generate icon components on demand from Iconify.
* [unplugin-inject-preload](https://github.com/Applelo/unplugin-inject-preload) ⭐ 39 | 🐛 2 | 🌐 TypeScript | 📅 2024-12-15: Inject `<link rel="preload">` to your index.html based on your build assets. Need to be used with HTMLWebpackPlugin or HTMLRspackPlugin.
* [unplugin-favicons](https://github.com/anolilab/unplugin-favicons) ⭐ 10 | 🐛 25 | 🌐 TypeScript | 📅 2026-10-30: Generate favicons for your project with caching for blazing fast rebuilds.
* [unplugin-build-info](https://github.com/renzp94/unplugin-build-info) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2024-09-05: Print the build information on the console.
* [unplugin-ata](https://github.com/ata-core/unplugin-ata) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2026-10-29: Compile JSON Schema files into standalone ata-validator modules with TypeScript declarations at build time.
* [unplugin-build-meta](https://github.com/luxass/unplugin-build-meta) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2026-10-30: Import build metadata into your JavaScript/TypeScript projects.
* [@arco-plugins/unplugin-react](https://www.npmjs.com/package/@arco-plugins/unplugin-react): A plugin to help you use Arco Design React.
* [@formatjs/unplugin](https://www.npmjs.com/package/@formatjs/unplugin): Universal build plugin for FormatJS.
* [@stylexjs/unplugin](https://www.npmjs.com/package/@stylexjs/unplugin): Universal bundler plugin for StyleX.
* [@tanstack/router-plugin](https://www.npmjs.com/package/@tanstack/router-plugin): Automatically generate configuration for TanStack Router.
* [unplugin-vue](https://www.npmjs.com/package/unplugin-vue): Transform Vue 3 SFC to JavaScript.

## Rstest Adapters

* [@modern-js/adapter-rstest](https://github.com/web-infra-dev/modern.js/tree/main/packages/cli/adapter-rstest) ⭐ 5,050 | 🐛 54 | 🌐 TypeScript | 📅 2026-10-30: Rstest adapter for Modern.js configuration.
* [@rstest/adapter-rsbuild](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rsbuild) ⭐ 513 | 🐛 30 | 🌐 TypeScript | 📅 2026-10-30: Rstest adapter for Rsbuild configuration.
* [@rstest/adapter-rslib](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rslib) ⭐ 513 | 🐛 30 | 🌐 TypeScript | 📅 2026-10-30: Rstest adapter for Rslib configuration.
* [@rstest/adapter-rspack](https://github.com/web-infra-dev/rstest/tree/main/packages/adapter-rspack) ⭐ 513 | 🐛 30 | 🌐 TypeScript | 📅 2026-10-30: Rstest adapter for Rspack configuration.

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

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-30._
