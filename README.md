## C Project Bootstrapping & Build Tooling

This [Taskfile](https://taskfile.dev/) will bootstrap a C project structure that can be easily rebuilt and tested by leveraging the available `tasks`.

Some of the convenience features provided by this Taskfile are as follows:

- Project structure initialization
- LSP support for structured C projects using [Neovim](https://github.com/gh0stsrc/nvim)
- Compiling and linking modules in various modes (production builds, local testing builds, unsafe builds)
- Testing of compiled and linked elf

