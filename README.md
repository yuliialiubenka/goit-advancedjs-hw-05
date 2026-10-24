# goit-advancedjs-hw-05

Educational project for setting up a TypeScript development environment.

## Installation

Node.js and TypeScript are required. They are already installed globally in this environment.

To install local dependencies, run:

```bash
npm install
```

## Commands

```bash
npm run build   # compiles src/*.ts into dist/*.js
npm run watch   # recompiles files after changes
```

The compiler is configured in `tsconfig.json`. The `sourceMap: true` option
creates `.js.map` files in the `dist` directory, allowing the original
TypeScript code to be debugged in the browser.
