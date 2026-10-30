---
name: sleet-js-setup
description: Source of truth for setting up and publishing sleet-js packages. Use this skill whenever you are creating a new sleet-js / sleet.near package or npm library, writing its README, setting up the build (dist output), or preparing it for publish (bun publish, npm login, tsc). Also use it when the user mentions a sleet-js package, sleet.near repo setup, package.json scripts for a sleet project, or the "bun i / bun run build / bun publish --dry-run" workflow.
---

# SLEET JS

Your source of truth for creating sleet-js packages

#### details

- build is output to the dist folder

#### readme format

```md
# repo-or-project-name-usually-matches-remote

one line description
```

this code block in the readme somewhere: (one to two line diffence is ok if the build command is different, make sure the codeblock is right, i sometimes copy this from porject to projcect without checking if right)

```sh
bun i
# bun run build
bun run tsc
# publish
bun publish --dry-run
bunx npm login
bun publish --access public
# other
bun run tsc --noEmit
bunx prettier . --write
```

this footer

```md
=====================
<br/>
copyright 2026 by sleet.near
```

=====================
<br/>
copyright 2026 by sleet.near
