**********
Change Log
**********

Notable project changes since release 1.3.1 (2017-02-22).


Unreleased
=========

Added
-----

- MPI-parallelisation.

- Improved thread-parallesation.

- Tool straingen for straining periodic gen-files.

- Shutdown possibility when using socket driver.


Changed
-------

- Using allocatables instead of pointers whenever possible.

- Change to Fypp-preprocessor


Fixed
-----

- Keyword Atoms in modes_in.hsd consider only the first specified entry

- Excited window selection in Cassida time-dependent calculation


17.1 (2017-06-16)
=================

Added
-----

- Add dptools toolkit.


Changed
-------

- Convert to LGPL 3 license.

- Restructure source tree.

- Streamline autotest suite and build system.


Fixed
-----

- Skip irrelevant tests that give false positives for particular compilation
  modes.

- Make geometry writing in gen and xyz files consistent.
