# exe2fbin

It turns out that `exe2fbin` is a modified version of Chris Dunford's `exe2com 1.04`;
in particular, most of the EXE header checks have been removed.

As `exe2com 1.04` is public domain, this repository provides an open-source equivalent
to `exe2fbin`, which also happens to compile with modern C compilers. Note that
big-endian CPUs are not supported.

## Changes relative to exe2fbin

* Added support for modern C compilers.
* Updated to `exe2com 1.05`.
  * Added `/R` option to print the relocation map.

## License

Public domain, as the original.
