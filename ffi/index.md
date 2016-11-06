Foreign Function Interface
==========================

Foreign Function Interface, FFI for short is the methodology to call
external code not written in Rust. It is often dubbed as "Native
code", which for interpreted or VM based language is valid. But kind
of a misnomer in Rust. As of today, these foreign function mostly
conform to C language calling conventions.

Using FFI involve mapping types, usually C types, to Rust, aswell as
adapting to the calling conventions and name mangling to locate
symbols in shared libraries.

Lot of languages, Python, C#, Ruby and even JavaScript in NodeJS offer
some sort of "CType" API that facilitate calling external functions
using C calling convention, like system API. Rust isn't foreign to
that idea.



References
----------

* [Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/): a
  collection of FFI examples compiled by Jake Goulding.
* [Rust book: Foreign Function Interface](https://doc.rust-lang.org/book/ffi.html):
  the official documentation on Rust FFI.

