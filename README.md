# Profile
## Hanif Bin Ariffin
## hanif.ariffin.4326@gmail.com

List of projects that I worked on in no specific order.


# Projects

## ISO 14977 parser

A `Rust` library to parse EBNF that is (hopefully) fully ISO 14977 compliant.

Link to the repository: [iso_14977](https://github.com/hbina/iso_14977)

## riffu

A `Rust` library for dealing with `RIFF` file format.
This fork is a complete overhaul of the original library.
This fork is designed to have a cleaner interface, complete error propagations and gives users the option to either lazily or eagerly read into the file.

Link to the repository: [riffu](https://github.com/hbina/riffu)

## chisai

A program similar to `xxd` but can generate output for multiple types of programming languages. Is also multithreaded and about ~3x times faster than `xxd`.

Link to the repository: [chisai](https://github.com/hbina/chisai)

## otto_vec

A Rust library that provides a procedural macro that can automatically vectorize any pure functions.

Link to the repository: [otto_vec](https://github.com/hbina/otto_vec)

## hyoka

Generic REPL as a `Rust` library. One can use this library to implement pretty much any REPL one can think of. If you browse the examples folder, I have implemented a simple calculator and `Lisp`-like interpreter using it.

Link to the repository: [hyoka](https://github.com/hbina/hyoka)

## smolset

Space efficient set implementation that defaults to stack allocated buffer when the number of elements is small and transform into heap allocated set when required. This is a fork of the original library with better fallback perforamnce (because of the mode) and more features (including their tests and documentations).

Link to the repository: [smolset](https://github.com/hbina/smolset)

## diect-rs

A simple `Redis`-like dictionary containing values that is annotated to expire at some point.
This is convenient if one desires to have a simple service that can act as a cookie validity verifier.

Link to the repository: [diect-rs](https://github.com/hbina/diect-rs)

## pixieve-rs

An unofficial fork of (an abandoned) an unofficial library to interface with the `pixiv` image hosting website. I am planning on using this to create a GUI for `pixiv`. It is quite hard to reverse engineer the various `Python` libraries for its API because `pixiv` does not officially document them.

Link to the repository: [rustpixiv](https://github.com/hbina/rustpixiv)

## fatuous

Basic 3D rendering engine in `C++` and `OpenGL`. Able to cast shadows, normal mapping and all that trivial stuff. I have some experience with `Vulkan` as well.

Link to the repository: [fatuous](https://github.com/hbina/fatuous)

## aoihana

A bunch of macros to create generic containers in `C`. This is mostly just experimental stuff. `C` makes it very hard to do proper type-safe containers.

Link to the repository: [aoihana](https://github.com/hbina/aoihana)

## leetcode_cpp

My solutions to about ~100 `leetcode` problems.

Link to the repository: [leetcode_cpp](https://github.com/hbina/leetcode_cpp)

## akarithm

A bunch of template algorithms in C++ that I use to solve `leetcode` problems and that I should be in the standard library.

Link to the repository: [akarithm](https://github.com/hbina/akarithm)

## Misc. Projects

I have also regularly read/contribute to `cargo`, `godot` and various other random projects that I find interesting. I like to read the source code of small projects a lot.

I am top ~100 contributor to `godot` and ~1000 downloads of my libraries in `crates.io`.
