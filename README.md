# GitHub Actions workflow for compiling GNU toolchains

This GitHub Actions workflow allows you to compile a Binutils + GCC (with libgcc) + GDB toolchain for x86-64 Linux. The produced toolchain is geared towards low-level and operating system development, and is therefore built following the instructions on the [OSDev Wiki](https://wiki.osdev.org/GCC_Cross-Compiler).

## Instructions

 - Fork this repo.
 - Go to Actions, and run the `Build GNU toolchain` workflow.

The workflow allows the user to specify the toolchain's target platform, as well as the Binutils, GCC and GDB versions to be built. Once it's completed, the toolchain archive will be available, both as a CI artifact and a release of the repo.

Alternately, you can find a number of prebuilt binaries in the [Releases](https://github.com/itsmevjnk/gnu-toolchain/releases) page, which are built occasionally and are therefore not guaranteed to be the latest version.

## Contributing

Any contributions to this project are greatly appreciated. Pull requests and issues are welcome.

## License

The workflow script is distributed under the MIT License. See `LICENSE.md` for more information.

The prebuilt toolchain binaries in this repo are distributed under the included programs' respective licenses.
