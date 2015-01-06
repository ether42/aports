D/os packaging
______________

*core* repository is supposed to hold only minimal Linux userland stuff
required for hardware boot, basic libraries, shell and utilities
and tools required to rebuild core itself and build upper layers.
It consists of three main meta-packages:
 - dos-base - packages required to boot and minimal interactive shell
 - build-base - packages required to build programs
 - dos-sdk - packages needed to build packages (i.e. rebuild core)

