# learn_rs.compass <span id="">![Rust Project](https://img.shields.io/badge/RUST-gray?logo=rust&style=for-the-badge&logoColor=orange)</span>

<span id="license" style="display:flex; flex-direction:row; gap:1rem; justify-content:start;">[![License: GPL v3](https://img.shields.io/badge/LICENSE-GPL_v3-blue?logo=gnu&style=for-the-badge)](https://www.gnu.org/licenses/gpl-3.0)
[![License: AGPL v3](https://img.shields.io/badge/LICENSE-AGPL_v3-blue?logo=gnu&style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)</span>

## Description
A personal journey exploring Rust, from first steps to advanced concepts. This repo is split into three stages;
+ `Beginner` - hello-world (hi-there) program, variables, functions, control-flow, and simple modularity 
+ `Intermediate` - memory management, data-structure, error-handling, generics, traits, and file-IO.
+ `Advanced` - concurrency, parallelism, unsafe, low level, advance pattern, macros, metaprogramming, async, networking, ecosystem-FFI

## Disclaimer
> [!IMPORTANT]
> *All trademarks, third-party assets/logos, and brand names used in this repository/project are the property of their respective owners. This project is an independent educational resource and is not sanctioned, sponsored, or manage by any third-party trademark holders.*

## Feature
+ [x] [x00_beginner](https://github.com/jayoadonis/learn_rs.compass.x00_beginner.git)<span style="color:red; font+weight:bold">*</span> [IN_PROGRESS]
+ [ ] x01_intermediate
+ [ ] x02_advance 

## Requirement
- <a href="https://rust-lang.org/tools/install/">&#128279;rustup</a>

<!-- ## Installation -->

## Usage
```bash
$ git clone --recursive <repo-url>
$ cd <project-filepath>
$ git submodule update --init --recursive #REM: Do this if remote submodule failed to extract.
$ cd <submodule-project-filepath> #REM: One of the Cargo (root) workspace (e.g. x00_beginner, x01_intermediate, or x02_advanced)
```
```bash
$ cargo build -p <package_name> [--lib | --bin [<bin_crate_name>]]

$ cargo run -p <package_name> --bin [<bin_crate_name>]

#REM: unit-test
$ cargo test -p <package_name> [--lib | --bin [<bin_crate_name>]]

#REM: integration-test
$ cargo test -p <package_name> --test <integration_test_crate_name>

$ cargo clean -p <package_name>
``` 

<!-- ## License -->

<!-- ## How to contribute -->

<!-- ## Author and Maintainer -->