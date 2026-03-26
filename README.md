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

| Package | Updated to |
| ------- | ---------- |
|         |            |

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
