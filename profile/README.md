# The Popcorn2 OS

Popcorn2 is a hobby microkernel, written in Rust, designed and developed by @egkoppel.

Popcorn2 is made up of several subprojects, each in it's own repository:

- [xbstrap](http://github.com/popcorn-2/xbstrap) - The Popcorn build system gradually turning into a package manager
- [popcorn-2](http://github.com/popcorn-2/popcorn-2) - The kernel, bootloader, and crates needed to support the kernel
- [book](http://github.com/popcorn-2/book) - An in-progress `mdBook` book, explaining some of the design philosophy behind Popcorn2
- [specifications](http://github.com/popcorn-2/specifications) - Specifications for some Popcorn2 formats, such as Popcorn2 IPC Protocol files
- [pipc](http://github.com/popcorn-2/pipc) - The Popcorn2 IPC Protocol Compiler
- [core-protocols](http://github.com/popcorn-2/core-protocols) - Sources for the Popcorn2 IPC Protocol files needed for a typical installation

**Core userspace projects**
- [file-server](http://github.com/popcorn-2/file-server) - The VFS and `initd` daemon (intrinsically tangled together too much)
- [revolution](http://github.com/popcorn-2/revolution) - The Revolution compositor (though for now just a terminal multiplexer)
- [devman](http://github.com/popcorn-2/devman) - The Popcorn2 device manangement server

**Drivers**
- [ia32_acpi_root](http://github.com/popcorn-2/ia32_acpi_root) - Root bus driver for x86 and x86-64 ACPI based systems
- [pci](http://github.com/popcorn-2/pci) - PCI bus driver
- [i8042](http://github.com/popcorn-2/i8042) - i8042 PS/2 driver, supporting mice and keyboards

More information about each subproject can be found in the README is the corresponding repository.

Additionally, forks of several other repositories are kept here, with patches to support Popcorn2.
The major ones are:

- [llvm](http://github.com/popcorn-2/llvm-project) - C and C++ toolchain and C++ standard library
- [mlibc](http://github.com/popcorn-2/mlibc) - C standard library
- [rust](http://github.com/popcorn-2/rust) - Rust toolchain and standard library
- [libc (rust)](http://github.com/popcorn-2/libc-rs) - Rust C standard library bindings

## Other contributors

- @Beanie496
- @hiornso
- @workingjubilee
