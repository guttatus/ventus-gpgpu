# ventus-gpgpu
GPGPU processor supporting RISCV-V extension, developed with Chisel HDL

## Quick Start

Chisel development environment config tutorial comes from [chipsalliance/playground: chipyard in mill :P (github.com)](https://github.com/chipsalliance/playground)

0. Install dependencies and setup environments: `pacman -Syu --noconfirm make parallel wget cmake ninja mill dtc verilator git llvm clang lld protobuf antlr4 numactl`
1. Init and update dependences

```shell
cd ventus gpgpu
make init
make patch
```

2. to generate verilog file, use `mill playground.tests`