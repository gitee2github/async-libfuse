# async-libfuse

## Introduction
Asyncchronized libfuse in Rust

## Getting Started

### Compiling

After `git clone` this project, you can start compiling by the help of `cargo`:

```sh
cargo build
```

While compiling finished message pop up on terminal, you can get the executable file in `./target/debug/async_libfuse`.

### Usage

Commandline and flags of `async_libfuse` are:

```sh
async_libfuse <MOUNTPOINT>
```

`async_libfuse` accepts the `MOUNTPOINT`, mounts it with `type fuse` and starts the fuse server on it.

## How to Contribute

We are happy to provide guidance for the new contributors.

Please sign the [CLA](https://openeuler.org/en/cla.html) before contributing.

## Licensing

async-libfuse is licensed under the Mulan PSL v2.
