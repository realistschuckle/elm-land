# Elm Land

[![Npm package version](https://badgen.net/npm/v/elm-land?6)](https://npmjs.com/package/elm-land)
[![elm-land](https://github.com/elm-land/elm-land/actions/workflows/node.js.yml/badge.svg?)](https://github.com/elm-land/elm-land/actions/workflows/node.js.yml)
[![BSD-3 Clause](https://img.shields.io/github/license/elm-land/elm-land)](https://github.com/elm-land/elm-land/blob/main/LICENSE)

[![Discord](https://badgen.net/discord/members/vnmYFfySbH?icon=discord&label)](https://join.elm.land)
[![Twitter](https://badgen.net/badge/icon/twitter?icon=twitter&label&color=00acee)](https://twitter.com/elmland_)
[![GitHub](https://badgen.net/badge/icon/github?icon=github&label&color=4078c0)](https://www.github.com/elm-land/elm-land)

[![Elm Land: Reliable web apps for everyone](https://github.com/elm-land/elm-land/raw/main/docs/elm-land-banner.jpg)](https://elm.land)

## 🌱 About this fork

This is a friendly, thankful, and respectful fork of
[Elm Land](https://elm.land), solving one specific problem: **updating
dependencies**.

### How to use this fork

You can find the version of Elm Land with updated dependencies on the
[`updated-dependencies`](https://github.com/elm-land/elm-land/tree/updated-dependencies)
branch. To install it, give this a try.

```sh
npm install --save-dev "https://github.com/realistschuckle/elm-land.git#updated-dependencies"
```

### Updated contained in this fork

| Project                            | Package                 | Updated from       | Updated to          |
| ---------------------------------- | ----------------------- | ------------------ | ------------------- |
| `docs`                             | `vitepress`             | `1.0.0-rc.35`      | `1.6.4`             |
| `examples/05-user-auth/api-server` | `cors`                  | `2.8.5`            | `2.8.6`             |
| `examples/05-user-auth/api-server` | `express`               | `4.18.1`           | `5.2.1`             |
| `examples/05-user-auth/api-server` | `nodemon`               | `2.0.19`           | `3.1.4`             |
| `examples/07-working-withjs`       | `three`                 | `0.147.0`          | `0.183.0`           |
| `examples/11-error-reporting`      | `@sentry/browser`       | `7.19.0`           | `10.46.0`           |
| `examples/11-error-reporting`      | `@sentry/tracing`       | `7.19.0`           | `7.120.4`           |
| `examples/14-scss-and-assets`      | `concurrently`          | `7.6.0`            | `9.2.1`             |
| `examples/14-scss-and-assets`      | `sass`                  | `1.57.1`           | `1.98.0`            |
| `examples/19-tailwindcss`          | `autoprefiexer`         | `10.4.16`          | **removed**         |
| `examples/19-tailwindcss`          | `tailwindcss`           | `3.4.0`            | `4.2.2`             |
| `projects/cli`                     | `bats`                  | `1.7.0`            | `1.13.0`            |
| `projects/cli`                     | `@lydell/elm`           | `0.9.1-14`         | **removed**         |
| `projects/cli`                     | `elm`                   | **added**          | `0.19.1-6`          |
| `projects/cli`                     | `chokidar`              | `3.5.3`            | `5.0.0`             |
| `projects/cli`                     | `terser`                | `5.15.1`           | `5.46.1`            |
| `projects/cli`                     | `typescript`            | `4.9.3`            | `5.9.3`             |
| `projects/cli`                     | `vite`                  | `5.2.8`            | `8.0.3`             |
| `projects/cli`                     | `vite-plugin-elm-watch` | `1.3.3`            | `1.4.4`             |
| `projects/graphql`                 | `graphql`               | `16.6.0`           | `16.13.2`           |
| `projects/graphql`                 | `bats`                  | **added**          | `1.13.0`            |
| `projects/tooling/codegen`         | `elm`                   | `0.19.1-5`         | `0.19.1-6`          |
| `projects/tooling/codegen`         | `elm-doc-preview`       | `5.0.5`            | `6.0.1`             |
| `projects/tooling/codegen`         | `elm-test`              | `0.19.1-revision7` | `0.19.1-revision17` |
| `projects/tooling/elm-error-json`  | `@types/jest`           | `27.5.1`           | `30.0.0`            |
| `projects/tooling/elm-error-json`  | `@types/node`           | `17.0.35`          | `25.5.0`            |
| `projects/tooling/elm-error-json`  | `jest`                  | `28.1.0`           | `30.3.0`            |
| `projects/tooling/elm-error-json`  | `ts-jest`               | `28.0.3`           | `29.4.6`            |
| `projects/tooling/elm-error-json`  | `typescript`            | `4.9.3`            | `5.9.3`             |

### Why this fork exists

I really like Elm Land. I've used it pretty much since @ryan-haskell released
it because I'm a huge fan of [Elm](https://elm-lang.org). However, as is often
the case with Libre Software, for whatever reason, the software grows stale as
the world around it moves on. That is the main motivation for this fork: the
[`main`](https://github.com/realistschuckle/elm-land) branch of Elm Land
hasn't seen an update since 14 April 2024. So, I thought I'd try my hand at
helping out.

---

## Welcome to our repo

The code for this GitHub project is broken down into smaller projects:

- **[elm-land](./projects/cli/)** - The CLI tool, available at [npmjs.org/elm-land](https://npmjs.org/elm-land)
- **[@elm-land/docs](./docs/)** - The official website, available at [elm.land](https://elm.land)

### Tooling

This repo also includes a few tooling projects, separated out for anyone else
making tooling for Elm:

- **[@elm-land/elm-error-json](./projects/tooling/elm-error-json/)** - Render
  the Elm compiler's JSON error output as full-color HTML or colored ASCII
  terminal output

- **[@elm-land/codegen](./projects/tooling/codegen/)** - a lightweight codegen
  library used internally by the Elm Land CLI
