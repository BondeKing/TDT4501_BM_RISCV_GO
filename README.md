# TDT4501_BM_RISCV_GO
Go for bare metal RISCV ... (Features missing!)

I would have liked to provided a .zip with the whole project set up propeperly, but the .zip gets too big.

How To Set Up:

Go to https://github.com/embeddedgo/patch and set up the Go Patch by following the instrucions.

Make sure you call the root direcotry for Golang "goroot".

After applying the Patch, drag goroot over the goroot directory you have already set up and change duplcate files with what is provided in this Repository.

These changes should be enough to get the compilor to compile correctly for Qemu-Virtio systems.

This patch to the Go patch is expected to be used for a Qemu-Virtio machine: https://www.qemu.org/download/

For getting C to compile to bare metal RISCV, take a lookt at this blog: https://twilco.github.io/riscv-from-scratch/2019/04/27/riscv-from-scratch-2.html

Already compipled testfiles amd their source files, which where used in the report, are already provided in the .zip.

RISCV GDB: https://github.com/sifive/freedom-gdb-metal

For how to use this whole system, look in the report.
