# Nitro

Nitro is a Node.js application for simple and complex frontend development with a tiny footprint.
It provides a proven but flexible structure to develop your frontend code, even in a large team.

The codebase is split up in different packages, organized in a monorepo.
Besides the main functionality including a yeoman generator, this monorepo includes also example projects

* `packages/generator-nitro` (yeoman generator)
* `packages/nitro-app` (main serverside app)
* `packages/nitro-exporter` (nitro exporter package)
* `packages/nitro-gulp` (nitro gulp task runner)
* `packages/nitro-webpack` (nitro webpack config)
* `packages/project-nitro` (example project with handlebars rendering engine)
* `packages/project-nitro-twig` (example project with twig rendering engine)

## Getting started

Before using, you need of course [node](https://nodejs.org/) installed.  
Nitro and the Nitro generator are tested with the current 
["Active LTS" versions of node.js](https://github.com/nodejs/Release#release-schedule) (release 8.x).

1.  Install base project:

```
npm install
```

2.  Start example project:

```
cd packages/project-nitro
npm start
```

## Changelog

Recent changes can be viewed on Github on the [Releases Page](https://github.com/namics/generator-nitro/releases)
