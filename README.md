# ts-schema-generator
Generates TypeScript schemas and types

## Requirements

### Node Versions
Node 16.10 or higher is required when importing as CommonJS modules.

### Installing/Publishing Packages
This repository comes with a `.npmrc.example` file at the root level. If you need to install and/or publish `@alvinquach` packages for the module, make a copy of the file in the same directory and rename it to `.npmrc`. Then, go into file and replace `TOKEN` with your personal access token in the following line:

```//npm.pkg.github.com/:_authToken=TOKEN```

This is required for both installing and publishing the `@alvinquach` packages.

Also do not forget to increment version number before publishing.

## Tests
If VSCode cannot find the types for jest, run `npm install` at the root directory.
