# e2p-sys: Low-level Rust bindings for libe2p from e2fsprogs

[![Build Status](https://travis-ci.com/michaellass/e2p-sys.svg?branch=master)](https://travis-ci.com/michaellass/e2p-sys)

This crate makes available functionality from libe2p. The bindings are automatically created by bindgen.

## Requirements
Bindgen requires libclang to generate the required code.

## Intended Use
This crate should not be used directly. It's intended to be used to form higher-level abstractions.
