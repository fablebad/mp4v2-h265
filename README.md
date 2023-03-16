# mp4v2-h265

#### 编译 海思平台下

网上比较流行的那份很旧的编译脚本用起来会报错，这里提供了一份可用脚本，并修改了编译器的冲突

```shell
./configure --host=arm-linux --prefix=/home/hisi/mp4v2_out/ --disable-option-checking --disable-debug --disable-optimize --disable-fvisibility --disable-gch --disable-largefile --disable-util --disable-dependency-tracking --disable-libtool-lock CC=aarch64-himix100-linux-gcc CXX=aarch64-himix100-linux-g++
```

