# Moleculer template: `project-typescript`

:mortar_board: Moleculer-based microservices project template for Typescript project.

## Features

- Moleculer v0.13.x with full-detailed `moleculer.config.ts` file.
- Common project with a demo `greeter` service.
- Optional API Gateway service.
- Optional Transporter & Cacher.
- Docker & Docker Compose files.
- Unit tests with [Jest](http://facebook.github.io/jest/).
- Lint with [TSLint](https://palantir.github.io/tslint/).
- Launch file for debugging in [VSCode](https://code.visualstudio.com/).

## Install

To install use the [moleculer-cli](https://github.com/moleculerjs/moleculer-cli) tool.

```bash
$ moleculer init randomnerd/moleculer-template-project-typescript my-project
```

## Prompts

```
$ moleculer init project-typescript moleculer-demo

Template repo: moleculerjs/moleculer-template-project-typescript
? Add API Gateway (moleculer-web) service Yes
? Would you like to communicate with other nodes? Yes
? Select a transporter TCP
? Would you like to use cache? No
? Add Docker files? Yes
? Use TSLint to lint your code? Yes
? Setup unit tests with Jest? Yes
Create 'moleculer-demo' folder...
? Would you like to run 'npm install'? Yes
```

## NPM scripts

- `npm run dev` - Start development mode (load all services locally with hot-reload & REPL)
- `npm run build`- Uses typescript to transpile service to javascript
- `npm start` - Start production mode (set `SERVICES` env variable to load certain services) (previous build needed)
- `npm run cli`: Start a CLI and connect to production. Don't forget to set production namespace with `--ns` argument in script
- `npm run lint` - Run TSLint
- `npm run ci` - Run continuous test mode with watching
- `npm test` - Run tests & generate coverage report
- `npm run dc:up`: Start the stack with Docker Compose
- `npm run dc:down`: Stop the stack with Docker Compose

## License

moleculer-template-project-typescript is available under the [MIT license](https://tldrlegal.com/license/mit-license).

## Contact

Copyright (c) 2018 MoleculerJS

[![@moleculerjs](https://img.shields.io/badge/github-moleculerjs-green.svg)](https://github.com/moleculerjs) [![@MoleculerJS](https://img.shields.io/badge/twitter-MoleculerJS-blue.svg)](https://twitter.com/MoleculerJS)
