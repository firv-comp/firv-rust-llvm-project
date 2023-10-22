Firv Readme
===

Latest llvm upstream commit: `f225471c68881d31835a06c6b2f2b40bdaa287d5`

Configure:
```
cmake -S llvm -B build -G Ninja -DCMAKE_BUILD_TYPE=Debug -DLLVM_TARGETS_TO_BUILD="RISCV;X86"
```

The `-DLLVM_TARGETS_TO_BUILD="RISCV;X86"` flag reduces the number of targets that are built, for shorter compilation time.

Build (ninja):
```
ninja -C build
```
