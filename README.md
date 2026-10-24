# @x12i/memorix-pipeline-orchestrator usage example

Memorix pipeline step registry, graph helpers, and run/execute engine.

This consuming application demonstrates **order a pipeline and identify steps ready after each dependency** using the published npm package, pinned to `1.1.0`.

## Run

Requires Node.js 24 or newer and npm. The example needs no service credentials.

```sh
npm install --ignore-scripts
npm start
```

## Example

[`src/index.mjs`](src/index.mjs) contains the complete example. Assertions check the demonstrated behavior and the program prints a small result.

## When to use the package

- Register a pipeline step and resolve its execution graph.
- Run the graph through the package's execution engine.

## Links

- [npm package](https://www.npmjs.com/package/@x12i/memorix-pipeline-orchestrator)

The `package.json` in this repository is private to prevent accidental publication of the example application under an npm package name.

## Validation scope

This example uses synthetic records and local callbacks or in-memory state. It checks the demonstrated consumer behavior of the pinned npm release. It does not connect to MongoDB, Catalox, a device, an AI provider, or a deployed pipeline service.
