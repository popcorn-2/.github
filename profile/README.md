# The Popcorn2 OS

Popcorn2 is a hobby microkernel, written in Rust, designed and developed by @egkoppel.

Popcorn2 is made up of several subprojects, each in it's own repository:

- [popcorn-2](http://github.com/popcorn-2/popcorn-2) - The kernel, bootloader, and crates needed to support the kernel
- [book](http://github.com/popcorn-2/book) - An in-progress `mdBook` book, explaining some of the design philosophy behind Popcorn2
- [specifications](http://github.com/popcorn-2/specifications) - Specifications for some Popcorn2 formats, such as Popcorn2 IPC Protocol files
- [pipc](http://github.com/popcorn-2/pipc) - The Popcorn2 IPC Protocol Compiler
- [core-protocols](http://github.com/popcorn-2/core-protocols) - Sources for the Popcorn2 IPC Protocol files needed for a typical installation

More information about each subproject can be found in the README is the corresponding repository.

Additionally, forks of several other repositories are kept here, with patches to support Popcorn2.
The major ones are:

- [llvm](http://github.com/popcorn-2/llvm-project) - C and C++ toolchain and C++ standard library
- [mlibc](http://github.com/popcorn-2/mlibc) - C standard library
- [rust](http://github.com/popcorn-2/rust) - Rust toolchain and standard library
- [libc (rust)](http://github.com/popcorn-2/libc-rs) - Rust C standard library bindings

## Contributors

- @bluewhale64
- @hiornso
- @workingjubilee
