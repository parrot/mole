# Mole TODO

These TODO items should be made Github Issues.

* assess lucian's proposal in https://github.com/cotto/mole/commit/2ac675a59db81d9185e848001c5d0266ea4ae750
* finish reading on how Go's references and arrays work - 
* look at lucian's ffi concept https://github.com/lucian1900/mole/commit/a0e480acf1df3c84f32c3bbda5487090a3d8cbef
* look at a tool that uses libffi for ffi (python's libgit2 bindings, e.g.)
* list criteria for completion
  - when is it worth starting to build a mole compiler
  - when is it worth calling the langauge final
* decide how to write the compiler
  - something that generates C is preferable
  - flex/bison is ugly but common
  - maybe lemon and/or re2c
