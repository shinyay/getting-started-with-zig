# Getting Started with Zig

This repository is just a hello world things related to Zig.

## Description

Here's a little something I learned today about Zig.

### What is Zig

> Zig is a general-purpose programming language and toolchain for maintaining robust, optimal and reusable software.

> Zig is a minimal open-source, fully-featured systems programming language presented as a friendlier alternative to C. It has a minimal Rust-like syntax but maintains C’s simplicity.

### Installation

- Zig

```shell
brew install zig
```

- Zig Visual Studio Code Extension
  - <https://marketplace.visualstudio.com/items?itemName=ziglang.vscode-zig>

- Zig version (as of today): `0.11.0`

```shell
zig version

0.11.0
```

### Hello World

#### 1. Create a Project

```shell
zig init-exe
```

```shell
info: Created build.zig
info: Created src/main.zig
info: Next, try `zig build --help` or `zig build run`
```

#### 2. Build and Run a Project

```shell
zig build run
```

```shell
All your codebase are belong to us.
Run `zig build test` to run the tests.
```

#### 3. Project Tree

```shell
hello-zig/
├── build.zig
├── src
│   └── main.zig
├── zig-cache
│   ├── h
│   │   ├── 3054aebf2decda3508f60a8c63b33834.txt
│   │   ├── 42ad41ca99580a09fb29d6e973803a65.txt
│   │   └── timestamp
│   ├── o
│   │   ├── 74c27f1902f95e35c91bb05395a1a801
│   │   │   └── dependencies.zig
│   │   ├── 97eaf9e7b39acd2f6b89098d81acc854
│   │   │   └── builtin.zig
│   │   ├── b64c864e55217e095d70d0d1031142ba
│   │   │   └── builtin.zig
│   │   ├── c767af0a4f9c83a00da3bfe82f3a2529
│   │   │   ├── hello-zig
│   │   │   └── hello-zig.o
│   │   └── e7f44074ff6445eff1a7fa11294b054a
│   │       ├── build
│   │       └── build.o
│   ├── tmp
│   └── z
│       ├── 422b7cc7dfd23003fdfe7314599cf950
│       └── b78f88b24cc6c1a13507ecfccf9702c3
└── zig-out
    └── bin
        └── hello-zig
```
## Demo



## Features

- feature:1
- feature:2

## Requirement

## Usage

## Installation

## References

- [Zig Standard Library](https://ziglang.org/documentation/master/std/#A;std)

## Licence

Released under the [MIT license](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/34c6fdd50d54aa8e23560c296424aeb61599aa71/LICENSE)

## Author

- github: <https://github.com/shinyay>
- twitter: <https://twitter.com/yanashin18618>
- mastodon: <https://mastodon.social/@yanashin>
