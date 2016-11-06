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




References
----------

* [Rust FFI Ominbus](http://jakegoulding.com/rust-ffi-omnibus/): a
collection of FFI examples compiled by Jake Goulding.


