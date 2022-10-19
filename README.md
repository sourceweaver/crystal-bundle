# crystal-bundle
[![Build Status](https://dl.circleci.com/status-badge/img/gh/sourceweaver/crystal-bundle/tree/master.svg?style=shield)](https://dl.circleci.com/status-badge/redirect/gh/sourceweaver/crystal-bundle/tree/master)

A bundle of statically linked builds of:

+ [Crystal compiler](https://github.com/crystal-lang/crystal) compiled using`glibc` and `LLVM14`
+ [Shards](https://github.com/crystal-lang/shards)
+ [Crystalline](https://github.com/elbywan/crystalline)

## Usage 

You can download the latest tarball from the [releases](https://github.com/sourceweaver/crystal-bundle/releases) page. The recipe of the builds are defined in `circleci/config.yml` and the build service used is CircleCI.

## Todo

- [ ] Add `musl` builds
