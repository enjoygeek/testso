testso
======

手动写Makefile编译Android NDK的so

之所以摒弃NDK，是因为NDK编译出来的so太大，而且导出表总有一些没用的符号。
而且手动编译的话，可以得到编译过程中间的.i和.s文件，可以删除一些没用的汇编代码。
