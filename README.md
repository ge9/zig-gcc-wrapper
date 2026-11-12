# zig-gcc-wrapper
Build with zig something that can be built with gcc or g++
### Usage

```
zigbuild 2.17 ./configure
zigmake 2.17 all
```
### shim
zigbuild 2.2.3 zcc -fno-sanitize=undefined -c -o xxxxxx.o cpucount.c 