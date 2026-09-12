# sistools.Rust <!-- omit in toc -->

Synesis Information Systems developer tools, for Rust

![Language](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
[![Crates.io](https://img.shields.io/crates/v/sistools.svg)](https://crates.io/crates/sistools)
[![GitHub release](https://img.shields.io/github/v/release/synesissoftware/sistools.Rust.svg)](https://github.com/synesissoftware/sistools.Rust/releases/latest)
![MSRV](https://img.shields.io/badge/MSRV-1.74-lightgrey)
[![CI](https://github.com/synesissoftware/sistools.Rust/actions/workflows/ci.yml/badge.svg)](https://github.com/synesissoftware/sistools.Rust/actions/workflows/ci.yml)
[![docs.rs](https://docs.rs/sistools/badge.svg)](https://docs.rs/sistools)


## Table of Contents <!-- omit in toc -->

- [Introduction](#introduction)
- [Installation](#installation)
- [Components](#components)
  - [Constants](#constants)
  - [Enumerations](#enumerations)
  - [Features](#features)
  - [Functions](#functions)
  - [Macros](#macros)
  - [Structures](#structures)
  - [Traits](#traits)
- [Examples](#examples)
- [Project Information](#project-information)
  - [Where to get help](#where-to-get-help)
  - [Contribution guidelines](#contribution-guidelines)
  - [Minimum Supported Rust Version (MSRV)](#minimum-supported-rust-version-msrv)
  - [Dependencies](#dependencies)
    - [Efferent (fan-out)](#efferent-fan-out)
    - [Build Dependencies](#build-dependencies)
    - [Development Dependencies](#development-dependencies)
    - [Afferent (fan-in)](#afferent-fan-in)
  - [Related projects](#related-projects)
  - [License](#license)


## Introduction

**sistools.Rust** provides Synesis Information Systems developer tools and build utilities for Rust projects.


## Installation

Reference in **Cargo.toml** in the usual way:

```toml
sistools = { version = "0.0" }
```


## Components

### Constants

None defined at this time.


### Enumerations

None defined at this time.


### Features

The following crate features are defined:

* `null-feature` — a feature that has no effect (useful for simplifying driver scripts);


### Functions

None defined at this time.


### Macros

None defined at this time.


### Structures

None defined at this time.


### Traits

None defined at this time.


## Examples

Examples can be found in `examples/`:

* `examples/versions/main.rs` — shows version identification and compilation details;


## Project Information

### Where to get help

[GitHub Page](https://github.com/synesissoftware/sistools.Rust "GitHub Page")


### Contribution guidelines

Defect reports, feature requests, and pull requests are welcome on https://github.com/synesissoftware/sistools.Rust.


### Minimum Supported Rust Version (MSRV)

The declared Minimum Supported Rust Version (MSRV) for **sistools.Rust** is **1.74**.

This MSRV guarantee applies to the library crate itself, its runtime dependencies (`[dependencies]`), and its build dependencies (`[build-dependencies]`). Downstream consumers compiling this crate as a dependency are guaranteed that it builds cleanly on the declared MSRV toolchain.

Development dependencies (`[dev-dependencies]`, such as benchmarking frameworks like **criterion**) may require newer Rust toolchains for local development or performance testing. These dev-dependencies are never fetched or compiled by downstream consumers and do not affect the library's MSRV guarantee.


### Dependencies

#### Efferent (fan-out)

Libraries upon which **sistools.Rust** depends:

* None currently.


#### Build Dependencies

None currently.


#### Development Dependencies

None currently.


#### Afferent (fan-in)

None currently.


### Related projects

None currently.


### License

**sistools.Rust** is released under the 3-clause BSD license. See [LICENSE](./LICENSE) for details.


<!-- ########################### end of file ########################### -->
