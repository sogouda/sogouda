# Sogouda

♥ Create lightweight desktop apps using HTML/CSS/[TS](https://www.typescriptlang.org/) ♥

## Packages

### [Rust](https://www.rust-lang.org/learn)

* [`sogouda`](#core-library) - The core library (written in [Rust](https://www.rust-lang.org/learn)).

### JavaScript/[TypeScript](https://www.typescriptlang.org/)

* [`sogouda`](#javascripttypescript-api) - A high-level library for [Sogouda](#sogouda) written in [TypeScript](https://www.typescriptlang.org/).
* [`@sogouda/bindings`](#javascripttypescript-bindings) - [TypeScript](https://www.typescriptlang.org/) bindings for [`sogouda`](#core-library).

## Core Library

The core library, [`sogouda`](https://crates.io/crates/sogouda), is written in [Rust](https://www.rust-lang.org/learn) to enhance compatibility, performance, and security.
Bindings for `sogouda` are available for different programming languages.

[The source code is available on GitHub.](#sogouda)

## Bindings

[Sogouda](#sogouda) is a framework for creating lightweight desktop apps using the familiar web development stack.
Bindings are provided to use [Sogouda](#sogouda) with various programming language.

### JavaScript/[TypeScript](https://www.typescriptlang.org/) Bindings

The bindings, [`@sogouda/bindings`](https://npmjs.org/package/@sogouda/bindings), are written in [Rust](https://www.rust-lang.org/learn) to enhance compatibility, performance, and security.
Type definitions are written in [TypeScript](https://www.typescriptlang.org/) and compiled into a `.d.ts` file to accompany [`index.node`](https://github.com/sogouda/node-bindings#indexnode).

[The source code is available on GitHub.](https://github.com/sogouda/node-bindings)

#### `index.node`

In [`@sogouda/bindings`](#bindings), there exists a file called [`index.node`](https://github.com/sogouda/node-bindings/tree/release/index.node) in the root directory of the package.
This file contains the compiled bindings to [the core library](#core-library). Essentially, this file acts as a bridge between [Rust](https://www.rust-lang.org/learn) and JavaScript/[TypeScript](https://www.typescriptlang.org/).


## JavaScript/[TypeScript](https://www.typescriptlang.org/) API

Sogouda exposes [a high-level JavaScript/TypeScript API](https://github.com/sogouda/node-sogouda/) written in [TypeScript](https://www.typescriptlang.org/).
This makes designing apps feel a lot more familiar to developers coming from Electron or other similar frameworks.
Type definitions are created in [TypeScript](https://www.typescriptlang.org/) and compiled into a `.d.ts` file to accompany the distributable files.

[The source code is available on GitHub.](https://github.com/sogouda/node-sogouda)

### Supported Runtimes

* [x] Node.js
* [ ] Deno
* [ ] bun
