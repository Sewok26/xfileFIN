The system is: Linux - 4.15.0-55-generic - x86_64
Compiling the C compiler identification source file "CMakeCCompilerId.c" succeeded.
Compiler: /usr/bin/cc 
Build flags: 
Id flags:  

The output was:
0


Compilation of the C compiler identification source "CMakeCCompilerId.c" produced "a.out"

The C compiler identification is GNU, found in "/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/3.14.5/CompilerIdC/a.out"

Compiling the CXX compiler identification source file "CMakeCXXCompilerId.cpp" succeeded.
Compiler: /usr/bin/c++ 
Build flags: 
Id flags:  

The output was:
0


Compilation of the CXX compiler identification source "CMakeCXXCompilerId.cpp" produced "a.out"

The CXX compiler identification is GNU, found in "/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/3.14.5/CompilerIdCXX/a.out"

Determining if the C compiler works passed with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_783bb/fast 
/usr/bin/make -f CMakeFiles/cmTC_783bb.dir/build.make CMakeFiles/cmTC_783bb.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_783bb.dir/testCCompiler.c.o
/usr/bin/cc    -o CMakeFiles/cmTC_783bb.dir/testCCompiler.c.o   -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp/testCCompiler.c
Linking C executable cmTC_783bb
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_783bb.dir/link.txt --verbose=1
/usr/bin/cc      CMakeFiles/cmTC_783bb.dir/testCCompiler.c.o  -o cmTC_783bb 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


Detecting C compiler ABI info compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_bab72/fast 
/usr/bin/make -f CMakeFiles/cmTC_bab72.dir/build.make CMakeFiles/cmTC_bab72.dir/build
make[1]: Entering directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp'
Building C object CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o
/usr/bin/cc   -v -o CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o   -c /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCCompilerABI.c
Using built-in specs.
COLLECT_GCC=/usr/bin/cc
OFFLOAD_TARGET_NAMES=nvptx-none
OFFLOAD_TARGET_DEFAULT=1
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) 
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/7/cc1 -quiet -v -imultiarch x86_64-linux-gnu /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCCompilerABI.c -quiet -dumpbase CMakeCCompilerABI.c -mtune=generic -march=x86-64 -auxbase-strip CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o -version -fstack-protector-strong -Wformat -Wformat-security -o /tmp/ccYSXrZ8.s
GNU C11 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)
	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP

GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
ignoring nonexistent directory "/usr/local/include/x86_64-linux-gnu"
ignoring nonexistent directory "/usr/lib/gcc/x86_64-linux-gnu/7/../../../../x86_64-linux-gnu/include"
#include "..." search starts here:
#include <...> search starts here:
 /usr/lib/gcc/x86_64-linux-gnu/7/include
 /usr/local/include
 /usr/lib/gcc/x86_64-linux-gnu/7/include-fixed
 /usr/include/x86_64-linux-gnu
 /usr/include
End of search list.
GNU C11 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)
	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP

GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
Compiler executable checksum: fa57db1fe2d756b22d454aa8428fd3bd
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64'
 as -v --64 -o CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o /tmp/ccYSXrZ8.s
GNU assembler version 2.30 (x86_64-linux-gnu) using BFD version (GNU Binutils for Ubuntu) 2.30
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64'
Linking C executable cmTC_bab72
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_bab72.dir/link.txt --verbose=1
/usr/bin/cc     -v CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o  -o cmTC_bab72 
Using built-in specs.
COLLECT_GCC=/usr/bin/cc
COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper
OFFLOAD_TARGET_NAMES=nvptx-none
OFFLOAD_TARGET_DEFAULT=1
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) 
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bab72' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/7/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNkhQa.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o cmTC_bab72 /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/7 -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/7/../../.. CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o
COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bab72' '-mtune=generic' '-march=x86-64'
make[1]: Leaving directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp'


Parsed C implicit include dir info from above output: rv=done
  found start of include info
  found start of implicit include info
    add: [/usr/lib/gcc/x86_64-linux-gnu/7/include]
    add: [/usr/local/include]
    add: [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
    add: [/usr/include/x86_64-linux-gnu]
    add: [/usr/include]
  end of search list found
  collapse include dir [/usr/lib/gcc/x86_64-linux-gnu/7/include] ==> [/usr/lib/gcc/x86_64-linux-gnu/7/include]
  collapse include dir [/usr/local/include] ==> [/usr/local/include]
  collapse include dir [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed] ==> [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
  collapse include dir [/usr/include/x86_64-linux-gnu] ==> [/usr/include/x86_64-linux-gnu]
  collapse include dir [/usr/include] ==> [/usr/include]
  implicit include dirs: [/usr/lib/gcc/x86_64-linux-gnu/7/include;/usr/local/include;/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed;/usr/include/x86_64-linux-gnu;/usr/include]


Parsed C implicit link information from above output:
  link line regex: [^( *|.*[/\])(ld|CMAKE_LINK_STARTFILE-NOTFOUND|([^/\]+-)?ld|collect2)[^/\]*( |$)]
  ignore line: [Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp]
  ignore line: []
  ignore line: [Run Build Command(s):/usr/bin/make cmTC_bab72/fast ]
  ignore line: [/usr/bin/make -f CMakeFiles/cmTC_bab72.dir/build.make CMakeFiles/cmTC_bab72.dir/build]
  ignore line: [make[1]: Entering directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp']
  ignore line: [Building C object CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o]
  ignore line: [/usr/bin/cc   -v -o CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o   -c /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCCompilerABI.c]
  ignore line: [Using built-in specs.]
  ignore line: [COLLECT_GCC=/usr/bin/cc]
  ignore line: [OFFLOAD_TARGET_NAMES=nvptx-none]
  ignore line: [OFFLOAD_TARGET_DEFAULT=1]
  ignore line: [Target: x86_64-linux-gnu]
  ignore line: [Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu]
  ignore line: [Thread model: posix]
  ignore line: [gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) ]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64']
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/cc1 -quiet -v -imultiarch x86_64-linux-gnu /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCCompilerABI.c -quiet -dumpbase CMakeCCompilerABI.c -mtune=generic -march=x86-64 -auxbase-strip CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o -version -fstack-protector-strong -Wformat -Wformat-security -o /tmp/ccYSXrZ8.s]
  ignore line: [GNU C11 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)]
  ignore line: [	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP]
  ignore line: []
  ignore line: [GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072]
  ignore line: [ignoring nonexistent directory "/usr/local/include/x86_64-linux-gnu"]
  ignore line: [ignoring nonexistent directory "/usr/lib/gcc/x86_64-linux-gnu/7/../../../../x86_64-linux-gnu/include"]
  ignore line: [#include "..." search starts here:]
  ignore line: [#include <...> search starts here:]
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/include]
  ignore line: [ /usr/local/include]
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
  ignore line: [ /usr/include/x86_64-linux-gnu]
  ignore line: [ /usr/include]
  ignore line: [End of search list.]
  ignore line: [GNU C11 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)]
  ignore line: [	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP]
  ignore line: []
  ignore line: [GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072]
  ignore line: [Compiler executable checksum: fa57db1fe2d756b22d454aa8428fd3bd]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64']
  ignore line: [ as -v --64 -o CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o /tmp/ccYSXrZ8.s]
  ignore line: [GNU assembler version 2.30 (x86_64-linux-gnu) using BFD version (GNU Binutils for Ubuntu) 2.30]
  ignore line: [COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/]
  ignore line: [LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o' '-c' '-mtune=generic' '-march=x86-64']
  ignore line: [Linking C executable cmTC_bab72]
  ignore line: [/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_bab72.dir/link.txt --verbose=1]
  ignore line: [/usr/bin/cc     -v CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o  -o cmTC_bab72 ]
  ignore line: [Using built-in specs.]
  ignore line: [COLLECT_GCC=/usr/bin/cc]
  ignore line: [COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper]
  ignore line: [OFFLOAD_TARGET_NAMES=nvptx-none]
  ignore line: [OFFLOAD_TARGET_DEFAULT=1]
  ignore line: [Target: x86_64-linux-gnu]
  ignore line: [Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu]
  ignore line: [Thread model: posix]
  ignore line: [gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) ]
  ignore line: [COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/]
  ignore line: [LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bab72' '-mtune=generic' '-march=x86-64']
  link line: [ /usr/lib/gcc/x86_64-linux-gnu/7/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper -plugin-opt=-fresolution=/tmp/ccWNkhQa.res -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lgcc_s --sysroot=/ --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o cmTC_bab72 /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/7 -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/7/../../.. CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o -lgcc --push-state --as-needed -lgcc_s --pop-state -lc -lgcc --push-state --as-needed -lgcc_s --pop-state /usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o]
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/collect2] ==> ignore
    arg [-plugin] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so] ==> ignore
    arg [-plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper] ==> ignore
    arg [-plugin-opt=-fresolution=/tmp/ccWNkhQa.res] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc_s] ==> ignore
    arg [-plugin-opt=-pass-through=-lc] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc_s] ==> ignore
    arg [--sysroot=/] ==> ignore
    arg [--build-id] ==> ignore
    arg [--eh-frame-hdr] ==> ignore
    arg [-m] ==> ignore
    arg [elf_x86_64] ==> ignore
    arg [--hash-style=gnu] ==> ignore
    arg [--as-needed] ==> ignore
    arg [-dynamic-linker] ==> ignore
    arg [/lib64/ld-linux-x86-64.so.2] ==> ignore
    arg [-pie] ==> ignore
    arg [-znow] ==> ignore
    arg [-zrelro] ==> ignore
    arg [-o] ==> ignore
    arg [cmTC_bab72] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o] ==> ignore
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib]
    arg [-L/lib/x86_64-linux-gnu] ==> dir [/lib/x86_64-linux-gnu]
    arg [-L/lib/../lib] ==> dir [/lib/../lib]
    arg [-L/usr/lib/x86_64-linux-gnu] ==> dir [/usr/lib/x86_64-linux-gnu]
    arg [-L/usr/lib/../lib] ==> dir [/usr/lib/../lib]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../..] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../..]
    arg [CMakeFiles/cmTC_bab72.dir/CMakeCCompilerABI.c.o] ==> ignore
    arg [-lgcc] ==> lib [gcc]
    arg [--push-state] ==> ignore
    arg [--as-needed] ==> ignore
    arg [-lgcc_s] ==> lib [gcc_s]
    arg [--pop-state] ==> ignore
    arg [-lc] ==> lib [c]
    arg [-lgcc] ==> lib [gcc]
    arg [--push-state] ==> ignore
    arg [--as-needed] ==> ignore
    arg [-lgcc_s] ==> lib [gcc_s]
    arg [--pop-state] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o] ==> ignore
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7] ==> [/usr/lib/gcc/x86_64-linux-gnu/7]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu] ==> [/usr/lib/x86_64-linux-gnu]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib] ==> [/usr/lib]
  collapse library dir [/lib/x86_64-linux-gnu] ==> [/lib/x86_64-linux-gnu]
  collapse library dir [/lib/../lib] ==> [/lib]
  collapse library dir [/usr/lib/x86_64-linux-gnu] ==> [/usr/lib/x86_64-linux-gnu]
  collapse library dir [/usr/lib/../lib] ==> [/usr/lib]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../..] ==> [/usr/lib]
  implicit libs: [gcc;gcc_s;c;gcc;gcc_s]
  implicit dirs: [/usr/lib/gcc/x86_64-linux-gnu/7;/usr/lib/x86_64-linux-gnu;/usr/lib;/lib/x86_64-linux-gnu;/lib]
  implicit fwks: []




Detecting C [-std=c11] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_b8421/fast 
/usr/bin/make -f CMakeFiles/cmTC_b8421.dir/build.make CMakeFiles/cmTC_b8421.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_b8421.dir/feature_tests.c.o
/usr/bin/cc   -std=c11 -o CMakeFiles/cmTC_b8421.dir/feature_tests.c.o   -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.c
Linking C executable cmTC_b8421
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_b8421.dir/link.txt --verbose=1
/usr/bin/cc      CMakeFiles/cmTC_b8421.dir/feature_tests.c.o  -o cmTC_b8421 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: C_FEATURE:1c_function_prototypes
    Feature record: C_FEATURE:1c_restrict
    Feature record: C_FEATURE:1c_static_assert
    Feature record: C_FEATURE:1c_variadic_macros


Detecting C [-std=c99] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_e1ca2/fast 
/usr/bin/make -f CMakeFiles/cmTC_e1ca2.dir/build.make CMakeFiles/cmTC_e1ca2.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_e1ca2.dir/feature_tests.c.o
/usr/bin/cc   -std=c99 -o CMakeFiles/cmTC_e1ca2.dir/feature_tests.c.o   -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.c
Linking C executable cmTC_e1ca2
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_e1ca2.dir/link.txt --verbose=1
/usr/bin/cc      CMakeFiles/cmTC_e1ca2.dir/feature_tests.c.o  -o cmTC_e1ca2 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: C_FEATURE:1c_function_prototypes
    Feature record: C_FEATURE:1c_restrict
    Feature record: C_FEATURE:0c_static_assert
    Feature record: C_FEATURE:1c_variadic_macros


Detecting C [-std=c90] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_0a8d8/fast 
/usr/bin/make -f CMakeFiles/cmTC_0a8d8.dir/build.make CMakeFiles/cmTC_0a8d8.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_0a8d8.dir/feature_tests.c.o
/usr/bin/cc   -std=c90 -o CMakeFiles/cmTC_0a8d8.dir/feature_tests.c.o   -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.c
Linking C executable cmTC_0a8d8
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_0a8d8.dir/link.txt --verbose=1
/usr/bin/cc      CMakeFiles/cmTC_0a8d8.dir/feature_tests.c.o  -o cmTC_0a8d8 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: C_FEATURE:1c_function_prototypes
    Feature record: C_FEATURE:0c_restrict
    Feature record: C_FEATURE:0c_static_assert
    Feature record: C_FEATURE:0c_variadic_macros
Determining if the CXX compiler works passed with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_6c346/fast 
/usr/bin/make -f CMakeFiles/cmTC_6c346.dir/build.make CMakeFiles/cmTC_6c346.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building CXX object CMakeFiles/cmTC_6c346.dir/testCXXCompiler.cxx.o
/usr/bin/c++     -o CMakeFiles/cmTC_6c346.dir/testCXXCompiler.cxx.o -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp/testCXXCompiler.cxx
Linking CXX executable cmTC_6c346
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_6c346.dir/link.txt --verbose=1
/usr/bin/c++       CMakeFiles/cmTC_6c346.dir/testCXXCompiler.cxx.o  -o cmTC_6c346 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


Detecting CXX compiler ABI info compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_bfb19/fast 
/usr/bin/make -f CMakeFiles/cmTC_bfb19.dir/build.make CMakeFiles/cmTC_bfb19.dir/build
make[1]: Entering directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp'
Building CXX object CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o
/usr/bin/c++    -v -o CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -c /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCXXCompilerABI.cpp
Using built-in specs.
COLLECT_GCC=/usr/bin/c++
OFFLOAD_TARGET_NAMES=nvptx-none
OFFLOAD_TARGET_DEFAULT=1
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) 
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/7/cc1plus -quiet -v -imultiarch x86_64-linux-gnu -D_GNU_SOURCE /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCXXCompilerABI.cpp -quiet -dumpbase CMakeCXXCompilerABI.cpp -mtune=generic -march=x86-64 -auxbase-strip CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -version -fstack-protector-strong -Wformat -Wformat-security -o /tmp/ccnb81TH.s
GNU C++14 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)
	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP

GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
ignoring duplicate directory "/usr/include/x86_64-linux-gnu/c++/7"
ignoring nonexistent directory "/usr/local/include/x86_64-linux-gnu"
ignoring nonexistent directory "/usr/lib/gcc/x86_64-linux-gnu/7/../../../../x86_64-linux-gnu/include"
#include "..." search starts here:
#include <...> search starts here:
 /usr/include/c++/7
 /usr/include/x86_64-linux-gnu/c++/7
 /usr/include/c++/7/backward
 /usr/lib/gcc/x86_64-linux-gnu/7/include
 /usr/local/include
 /usr/lib/gcc/x86_64-linux-gnu/7/include-fixed
 /usr/include/x86_64-linux-gnu
 /usr/include
End of search list.
GNU C++14 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)
	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP

GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072
Compiler executable checksum: 38816e3807cdcb3c59571e251bd6c090
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
 as -v --64 -o CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o /tmp/ccnb81TH.s
GNU assembler version 2.30 (x86_64-linux-gnu) using BFD version (GNU Binutils for Ubuntu) 2.30
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
Linking CXX executable cmTC_bfb19
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_bfb19.dir/link.txt --verbose=1
/usr/bin/c++      -v CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o  -o cmTC_bfb19 
Using built-in specs.
COLLECT_GCC=/usr/bin/c++
COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper
OFFLOAD_TARGET_NAMES=nvptx-none
OFFLOAD_TARGET_DEFAULT=1
Target: x86_64-linux-gnu
Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu
Thread model: posix
gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) 
COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/
LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/
COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bfb19' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
 /usr/lib/gcc/x86_64-linux-gnu/7/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXnzwEJ.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc --sysroot=/ --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o cmTC_bfb19 /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/7 -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/7/../../.. CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -lstdc++ -lm -lgcc_s -lgcc -lc -lgcc_s -lgcc /usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o
COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bfb19' '-shared-libgcc' '-mtune=generic' '-march=x86-64'
make[1]: Leaving directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp'


Parsed CXX implicit include dir info from above output: rv=done
  found start of include info
  found start of implicit include info
    add: [/usr/include/c++/7]
    add: [/usr/include/x86_64-linux-gnu/c++/7]
    add: [/usr/include/c++/7/backward]
    add: [/usr/lib/gcc/x86_64-linux-gnu/7/include]
    add: [/usr/local/include]
    add: [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
    add: [/usr/include/x86_64-linux-gnu]
    add: [/usr/include]
  end of search list found
  collapse include dir [/usr/include/c++/7] ==> [/usr/include/c++/7]
  collapse include dir [/usr/include/x86_64-linux-gnu/c++/7] ==> [/usr/include/x86_64-linux-gnu/c++/7]
  collapse include dir [/usr/include/c++/7/backward] ==> [/usr/include/c++/7/backward]
  collapse include dir [/usr/lib/gcc/x86_64-linux-gnu/7/include] ==> [/usr/lib/gcc/x86_64-linux-gnu/7/include]
  collapse include dir [/usr/local/include] ==> [/usr/local/include]
  collapse include dir [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed] ==> [/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
  collapse include dir [/usr/include/x86_64-linux-gnu] ==> [/usr/include/x86_64-linux-gnu]
  collapse include dir [/usr/include] ==> [/usr/include]
  implicit include dirs: [/usr/include/c++/7;/usr/include/x86_64-linux-gnu/c++/7;/usr/include/c++/7/backward;/usr/lib/gcc/x86_64-linux-gnu/7/include;/usr/local/include;/usr/lib/gcc/x86_64-linux-gnu/7/include-fixed;/usr/include/x86_64-linux-gnu;/usr/include]


Parsed CXX implicit link information from above output:
  link line regex: [^( *|.*[/\])(ld|CMAKE_LINK_STARTFILE-NOTFOUND|([^/\]+-)?ld|collect2)[^/\]*( |$)]
  ignore line: [Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp]
  ignore line: []
  ignore line: [Run Build Command(s):/usr/bin/make cmTC_bfb19/fast ]
  ignore line: [/usr/bin/make -f CMakeFiles/cmTC_bfb19.dir/build.make CMakeFiles/cmTC_bfb19.dir/build]
  ignore line: [make[1]: Entering directory '/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp']
  ignore line: [Building CXX object CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o]
  ignore line: [/usr/bin/c++    -v -o CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -c /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCXXCompilerABI.cpp]
  ignore line: [Using built-in specs.]
  ignore line: [COLLECT_GCC=/usr/bin/c++]
  ignore line: [OFFLOAD_TARGET_NAMES=nvptx-none]
  ignore line: [OFFLOAD_TARGET_DEFAULT=1]
  ignore line: [Target: x86_64-linux-gnu]
  ignore line: [Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu]
  ignore line: [Thread model: posix]
  ignore line: [gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) ]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64']
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/cc1plus -quiet -v -imultiarch x86_64-linux-gnu -D_GNU_SOURCE /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CMakeCXXCompilerABI.cpp -quiet -dumpbase CMakeCXXCompilerABI.cpp -mtune=generic -march=x86-64 -auxbase-strip CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -version -fstack-protector-strong -Wformat -Wformat-security -o /tmp/ccnb81TH.s]
  ignore line: [GNU C++14 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)]
  ignore line: [	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP]
  ignore line: []
  ignore line: [GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072]
  ignore line: [ignoring duplicate directory "/usr/include/x86_64-linux-gnu/c++/7"]
  ignore line: [ignoring nonexistent directory "/usr/local/include/x86_64-linux-gnu"]
  ignore line: [ignoring nonexistent directory "/usr/lib/gcc/x86_64-linux-gnu/7/../../../../x86_64-linux-gnu/include"]
  ignore line: [#include "..." search starts here:]
  ignore line: [#include <...> search starts here:]
  ignore line: [ /usr/include/c++/7]
  ignore line: [ /usr/include/x86_64-linux-gnu/c++/7]
  ignore line: [ /usr/include/c++/7/backward]
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/include]
  ignore line: [ /usr/local/include]
  ignore line: [ /usr/lib/gcc/x86_64-linux-gnu/7/include-fixed]
  ignore line: [ /usr/include/x86_64-linux-gnu]
  ignore line: [ /usr/include]
  ignore line: [End of search list.]
  ignore line: [GNU C++14 (Ubuntu 7.4.0-1ubuntu1~18.04.1) version 7.4.0 (x86_64-linux-gnu)]
  ignore line: [	compiled by GNU C version 7.4.0, GMP version 6.1.2, MPFR version 4.0.1, MPC version 1.1.0, isl version isl-0.19-GMP]
  ignore line: []
  ignore line: [GGC heuristics: --param ggc-min-expand=100 --param ggc-min-heapsize=131072]
  ignore line: [Compiler executable checksum: 38816e3807cdcb3c59571e251bd6c090]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64']
  ignore line: [ as -v --64 -o CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o /tmp/ccnb81TH.s]
  ignore line: [GNU assembler version 2.30 (x86_64-linux-gnu) using BFD version (GNU Binutils for Ubuntu) 2.30]
  ignore line: [COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/]
  ignore line: [LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o' '-c' '-shared-libgcc' '-mtune=generic' '-march=x86-64']
  ignore line: [Linking CXX executable cmTC_bfb19]
  ignore line: [/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_bfb19.dir/link.txt --verbose=1]
  ignore line: [/usr/bin/c++      -v CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o  -o cmTC_bfb19 ]
  ignore line: [Using built-in specs.]
  ignore line: [COLLECT_GCC=/usr/bin/c++]
  ignore line: [COLLECT_LTO_WRAPPER=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper]
  ignore line: [OFFLOAD_TARGET_NAMES=nvptx-none]
  ignore line: [OFFLOAD_TARGET_DEFAULT=1]
  ignore line: [Target: x86_64-linux-gnu]
  ignore line: [Configured with: ../src/configure -v --with-pkgversion='Ubuntu 7.4.0-1ubuntu1~18.04.1' --with-bugurl=file:///usr/share/doc/gcc-7/README.Bugs --enable-languages=c,ada,c++,go,brig,d,fortran,objc,obj-c++ --prefix=/usr --with-gcc-major-version-only --program-suffix=-7 --program-prefix=x86_64-linux-gnu- --enable-shared --enable-linker-build-id --libexecdir=/usr/lib --without-included-gettext --enable-threads=posix --libdir=/usr/lib --enable-nls --with-sysroot=/ --enable-clocale=gnu --enable-libstdcxx-debug --enable-libstdcxx-time=yes --with-default-libstdcxx-abi=new --enable-gnu-unique-object --disable-vtable-verify --enable-libmpx --enable-plugin --enable-default-pie --with-system-zlib --with-target-system-zlib --enable-objc-gc=auto --enable-multiarch --disable-werror --with-arch-32=i686 --with-abi=m64 --with-multilib-list=m32,m64,mx32 --enable-multilib --with-tune=generic --enable-offload-targets=nvptx-none --without-cuda-driver --enable-checking=release --build=x86_64-linux-gnu --host=x86_64-linux-gnu --target=x86_64-linux-gnu]
  ignore line: [Thread model: posix]
  ignore line: [gcc version 7.4.0 (Ubuntu 7.4.0-1ubuntu1~18.04.1) ]
  ignore line: [COMPILER_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/]
  ignore line: [LIBRARY_PATH=/usr/lib/gcc/x86_64-linux-gnu/7/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib/:/lib/x86_64-linux-gnu/:/lib/../lib/:/usr/lib/x86_64-linux-gnu/:/usr/lib/../lib/:/usr/lib/gcc/x86_64-linux-gnu/7/../../../:/lib/:/usr/lib/]
  ignore line: [COLLECT_GCC_OPTIONS='-v' '-o' 'cmTC_bfb19' '-shared-libgcc' '-mtune=generic' '-march=x86-64']
  link line: [ /usr/lib/gcc/x86_64-linux-gnu/7/collect2 -plugin /usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so -plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper -plugin-opt=-fresolution=/tmp/ccXnzwEJ.res -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc -plugin-opt=-pass-through=-lc -plugin-opt=-pass-through=-lgcc_s -plugin-opt=-pass-through=-lgcc --sysroot=/ --build-id --eh-frame-hdr -m elf_x86_64 --hash-style=gnu --as-needed -dynamic-linker /lib64/ld-linux-x86-64.so.2 -pie -z now -z relro -o cmTC_bfb19 /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o /usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o -L/usr/lib/gcc/x86_64-linux-gnu/7 -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu -L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib -L/lib/x86_64-linux-gnu -L/lib/../lib -L/usr/lib/x86_64-linux-gnu -L/usr/lib/../lib -L/usr/lib/gcc/x86_64-linux-gnu/7/../../.. CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o -lstdc++ -lm -lgcc_s -lgcc -lc -lgcc_s -lgcc /usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o /usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o]
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/collect2] ==> ignore
    arg [-plugin] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/liblto_plugin.so] ==> ignore
    arg [-plugin-opt=/usr/lib/gcc/x86_64-linux-gnu/7/lto-wrapper] ==> ignore
    arg [-plugin-opt=-fresolution=/tmp/ccXnzwEJ.res] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc_s] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc] ==> ignore
    arg [-plugin-opt=-pass-through=-lc] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc_s] ==> ignore
    arg [-plugin-opt=-pass-through=-lgcc] ==> ignore
    arg [--sysroot=/] ==> ignore
    arg [--build-id] ==> ignore
    arg [--eh-frame-hdr] ==> ignore
    arg [-m] ==> ignore
    arg [elf_x86_64] ==> ignore
    arg [--hash-style=gnu] ==> ignore
    arg [--as-needed] ==> ignore
    arg [-dynamic-linker] ==> ignore
    arg [/lib64/ld-linux-x86-64.so.2] ==> ignore
    arg [-pie] ==> ignore
    arg [-znow] ==> ignore
    arg [-zrelro] ==> ignore
    arg [-o] ==> ignore
    arg [cmTC_bfb19] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/Scrt1.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crti.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/crtbeginS.o] ==> ignore
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib]
    arg [-L/lib/x86_64-linux-gnu] ==> dir [/lib/x86_64-linux-gnu]
    arg [-L/lib/../lib] ==> dir [/lib/../lib]
    arg [-L/usr/lib/x86_64-linux-gnu] ==> dir [/usr/lib/x86_64-linux-gnu]
    arg [-L/usr/lib/../lib] ==> dir [/usr/lib/../lib]
    arg [-L/usr/lib/gcc/x86_64-linux-gnu/7/../../..] ==> dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../..]
    arg [CMakeFiles/cmTC_bfb19.dir/CMakeCXXCompilerABI.cpp.o] ==> ignore
    arg [-lstdc++] ==> lib [stdc++]
    arg [-lm] ==> lib [m]
    arg [-lgcc_s] ==> lib [gcc_s]
    arg [-lgcc] ==> lib [gcc]
    arg [-lc] ==> lib [c]
    arg [-lgcc_s] ==> lib [gcc_s]
    arg [-lgcc] ==> lib [gcc]
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/crtendS.o] ==> ignore
    arg [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu/crtn.o] ==> ignore
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7] ==> [/usr/lib/gcc/x86_64-linux-gnu/7]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../x86_64-linux-gnu] ==> [/usr/lib/x86_64-linux-gnu]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../../../lib] ==> [/usr/lib]
  collapse library dir [/lib/x86_64-linux-gnu] ==> [/lib/x86_64-linux-gnu]
  collapse library dir [/lib/../lib] ==> [/lib]
  collapse library dir [/usr/lib/x86_64-linux-gnu] ==> [/usr/lib/x86_64-linux-gnu]
  collapse library dir [/usr/lib/../lib] ==> [/usr/lib]
  collapse library dir [/usr/lib/gcc/x86_64-linux-gnu/7/../../..] ==> [/usr/lib]
  implicit libs: [stdc++;m;gcc_s;gcc;c;gcc_s;gcc]
  implicit dirs: [/usr/lib/gcc/x86_64-linux-gnu/7;/usr/lib/x86_64-linux-gnu;/usr/lib;/lib/x86_64-linux-gnu;/lib]
  implicit fwks: []




Detecting CXX [-std=c++1z] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_8d1ae/fast 
/usr/bin/make -f CMakeFiles/cmTC_8d1ae.dir/build.make CMakeFiles/cmTC_8d1ae.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building CXX object CMakeFiles/cmTC_8d1ae.dir/feature_tests.cxx.o
/usr/bin/c++    -std=c++1z -o CMakeFiles/cmTC_8d1ae.dir/feature_tests.cxx.o -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.cxx
Linking CXX executable cmTC_8d1ae
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_8d1ae.dir/link.txt --verbose=1
/usr/bin/c++       CMakeFiles/cmTC_8d1ae.dir/feature_tests.cxx.o  -o cmTC_8d1ae 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: CXX_FEATURE:1cxx_aggregate_default_initializers
    Feature record: CXX_FEATURE:1cxx_alias_templates
    Feature record: CXX_FEATURE:1cxx_alignas
    Feature record: CXX_FEATURE:1cxx_alignof
    Feature record: CXX_FEATURE:1cxx_attributes
    Feature record: CXX_FEATURE:1cxx_attribute_deprecated
    Feature record: CXX_FEATURE:1cxx_auto_type
    Feature record: CXX_FEATURE:1cxx_binary_literals
    Feature record: CXX_FEATURE:1cxx_constexpr
    Feature record: CXX_FEATURE:1cxx_contextual_conversions
    Feature record: CXX_FEATURE:1cxx_decltype
    Feature record: CXX_FEATURE:1cxx_decltype_auto
    Feature record: CXX_FEATURE:1cxx_decltype_incomplete_return_types
    Feature record: CXX_FEATURE:1cxx_default_function_template_args
    Feature record: CXX_FEATURE:1cxx_defaulted_functions
    Feature record: CXX_FEATURE:1cxx_defaulted_move_initializers
    Feature record: CXX_FEATURE:1cxx_delegating_constructors
    Feature record: CXX_FEATURE:1cxx_deleted_functions
    Feature record: CXX_FEATURE:1cxx_digit_separators
    Feature record: CXX_FEATURE:1cxx_enum_forward_declarations
    Feature record: CXX_FEATURE:1cxx_explicit_conversions
    Feature record: CXX_FEATURE:1cxx_extended_friend_declarations
    Feature record: CXX_FEATURE:1cxx_extern_templates
    Feature record: CXX_FEATURE:1cxx_final
    Feature record: CXX_FEATURE:1cxx_func_identifier
    Feature record: CXX_FEATURE:1cxx_generalized_initializers
    Feature record: CXX_FEATURE:1cxx_generic_lambdas
    Feature record: CXX_FEATURE:1cxx_inheriting_constructors
    Feature record: CXX_FEATURE:1cxx_inline_namespaces
    Feature record: CXX_FEATURE:1cxx_lambdas
    Feature record: CXX_FEATURE:1cxx_lambda_init_captures
    Feature record: CXX_FEATURE:1cxx_local_type_template_args
    Feature record: CXX_FEATURE:1cxx_long_long_type
    Feature record: CXX_FEATURE:1cxx_noexcept
    Feature record: CXX_FEATURE:1cxx_nonstatic_member_init
    Feature record: CXX_FEATURE:1cxx_nullptr
    Feature record: CXX_FEATURE:1cxx_override
    Feature record: CXX_FEATURE:1cxx_range_for
    Feature record: CXX_FEATURE:1cxx_raw_string_literals
    Feature record: CXX_FEATURE:1cxx_reference_qualified_functions
    Feature record: CXX_FEATURE:1cxx_relaxed_constexpr
    Feature record: CXX_FEATURE:1cxx_return_type_deduction
    Feature record: CXX_FEATURE:1cxx_right_angle_brackets
    Feature record: CXX_FEATURE:1cxx_rvalue_references
    Feature record: CXX_FEATURE:1cxx_sizeof_member
    Feature record: CXX_FEATURE:1cxx_static_assert
    Feature record: CXX_FEATURE:1cxx_strong_enums
    Feature record: CXX_FEATURE:1cxx_template_template_parameters
    Feature record: CXX_FEATURE:1cxx_thread_local
    Feature record: CXX_FEATURE:1cxx_trailing_return_types
    Feature record: CXX_FEATURE:1cxx_unicode_literals
    Feature record: CXX_FEATURE:1cxx_uniform_initialization
    Feature record: CXX_FEATURE:1cxx_unrestricted_unions
    Feature record: CXX_FEATURE:1cxx_user_literals
    Feature record: CXX_FEATURE:1cxx_variable_templates
    Feature record: CXX_FEATURE:1cxx_variadic_macros
    Feature record: CXX_FEATURE:1cxx_variadic_templates


Detecting CXX [-std=c++14] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_1ff14/fast 
/usr/bin/make -f CMakeFiles/cmTC_1ff14.dir/build.make CMakeFiles/cmTC_1ff14.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building CXX object CMakeFiles/cmTC_1ff14.dir/feature_tests.cxx.o
/usr/bin/c++    -std=c++14 -o CMakeFiles/cmTC_1ff14.dir/feature_tests.cxx.o -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.cxx
Linking CXX executable cmTC_1ff14
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_1ff14.dir/link.txt --verbose=1
/usr/bin/c++       CMakeFiles/cmTC_1ff14.dir/feature_tests.cxx.o  -o cmTC_1ff14 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: CXX_FEATURE:1cxx_aggregate_default_initializers
    Feature record: CXX_FEATURE:1cxx_alias_templates
    Feature record: CXX_FEATURE:1cxx_alignas
    Feature record: CXX_FEATURE:1cxx_alignof
    Feature record: CXX_FEATURE:1cxx_attributes
    Feature record: CXX_FEATURE:1cxx_attribute_deprecated
    Feature record: CXX_FEATURE:1cxx_auto_type
    Feature record: CXX_FEATURE:1cxx_binary_literals
    Feature record: CXX_FEATURE:1cxx_constexpr
    Feature record: CXX_FEATURE:1cxx_contextual_conversions
    Feature record: CXX_FEATURE:1cxx_decltype
    Feature record: CXX_FEATURE:1cxx_decltype_auto
    Feature record: CXX_FEATURE:1cxx_decltype_incomplete_return_types
    Feature record: CXX_FEATURE:1cxx_default_function_template_args
    Feature record: CXX_FEATURE:1cxx_defaulted_functions
    Feature record: CXX_FEATURE:1cxx_defaulted_move_initializers
    Feature record: CXX_FEATURE:1cxx_delegating_constructors
    Feature record: CXX_FEATURE:1cxx_deleted_functions
    Feature record: CXX_FEATURE:1cxx_digit_separators
    Feature record: CXX_FEATURE:1cxx_enum_forward_declarations
    Feature record: CXX_FEATURE:1cxx_explicit_conversions
    Feature record: CXX_FEATURE:1cxx_extended_friend_declarations
    Feature record: CXX_FEATURE:1cxx_extern_templates
    Feature record: CXX_FEATURE:1cxx_final
    Feature record: CXX_FEATURE:1cxx_func_identifier
    Feature record: CXX_FEATURE:1cxx_generalized_initializers
    Feature record: CXX_FEATURE:1cxx_generic_lambdas
    Feature record: CXX_FEATURE:1cxx_inheriting_constructors
    Feature record: CXX_FEATURE:1cxx_inline_namespaces
    Feature record: CXX_FEATURE:1cxx_lambdas
    Feature record: CXX_FEATURE:1cxx_lambda_init_captures
    Feature record: CXX_FEATURE:1cxx_local_type_template_args
    Feature record: CXX_FEATURE:1cxx_long_long_type
    Feature record: CXX_FEATURE:1cxx_noexcept
    Feature record: CXX_FEATURE:1cxx_nonstatic_member_init
    Feature record: CXX_FEATURE:1cxx_nullptr
    Feature record: CXX_FEATURE:1cxx_override
    Feature record: CXX_FEATURE:1cxx_range_for
    Feature record: CXX_FEATURE:1cxx_raw_string_literals
    Feature record: CXX_FEATURE:1cxx_reference_qualified_functions
    Feature record: CXX_FEATURE:1cxx_relaxed_constexpr
    Feature record: CXX_FEATURE:1cxx_return_type_deduction
    Feature record: CXX_FEATURE:1cxx_right_angle_brackets
    Feature record: CXX_FEATURE:1cxx_rvalue_references
    Feature record: CXX_FEATURE:1cxx_sizeof_member
    Feature record: CXX_FEATURE:1cxx_static_assert
    Feature record: CXX_FEATURE:1cxx_strong_enums
    Feature record: CXX_FEATURE:1cxx_template_template_parameters
    Feature record: CXX_FEATURE:1cxx_thread_local
    Feature record: CXX_FEATURE:1cxx_trailing_return_types
    Feature record: CXX_FEATURE:1cxx_unicode_literals
    Feature record: CXX_FEATURE:1cxx_uniform_initialization
    Feature record: CXX_FEATURE:1cxx_unrestricted_unions
    Feature record: CXX_FEATURE:1cxx_user_literals
    Feature record: CXX_FEATURE:1cxx_variable_templates
    Feature record: CXX_FEATURE:1cxx_variadic_macros
    Feature record: CXX_FEATURE:1cxx_variadic_templates


Detecting CXX [-std=c++11] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_8f0a5/fast 
/usr/bin/make -f CMakeFiles/cmTC_8f0a5.dir/build.make CMakeFiles/cmTC_8f0a5.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building CXX object CMakeFiles/cmTC_8f0a5.dir/feature_tests.cxx.o
/usr/bin/c++    -std=c++11 -o CMakeFiles/cmTC_8f0a5.dir/feature_tests.cxx.o -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.cxx
Linking CXX executable cmTC_8f0a5
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_8f0a5.dir/link.txt --verbose=1
/usr/bin/c++       CMakeFiles/cmTC_8f0a5.dir/feature_tests.cxx.o  -o cmTC_8f0a5 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: CXX_FEATURE:0cxx_aggregate_default_initializers
    Feature record: CXX_FEATURE:1cxx_alias_templates
    Feature record: CXX_FEATURE:1cxx_alignas
    Feature record: CXX_FEATURE:1cxx_alignof
    Feature record: CXX_FEATURE:1cxx_attributes
    Feature record: CXX_FEATURE:0cxx_attribute_deprecated
    Feature record: CXX_FEATURE:1cxx_auto_type
    Feature record: CXX_FEATURE:0cxx_binary_literals
    Feature record: CXX_FEATURE:1cxx_constexpr
    Feature record: CXX_FEATURE:0cxx_contextual_conversions
    Feature record: CXX_FEATURE:1cxx_decltype
    Feature record: CXX_FEATURE:0cxx_decltype_auto
    Feature record: CXX_FEATURE:1cxx_decltype_incomplete_return_types
    Feature record: CXX_FEATURE:1cxx_default_function_template_args
    Feature record: CXX_FEATURE:1cxx_defaulted_functions
    Feature record: CXX_FEATURE:1cxx_defaulted_move_initializers
    Feature record: CXX_FEATURE:1cxx_delegating_constructors
    Feature record: CXX_FEATURE:1cxx_deleted_functions
    Feature record: CXX_FEATURE:0cxx_digit_separators
    Feature record: CXX_FEATURE:1cxx_enum_forward_declarations
    Feature record: CXX_FEATURE:1cxx_explicit_conversions
    Feature record: CXX_FEATURE:1cxx_extended_friend_declarations
    Feature record: CXX_FEATURE:1cxx_extern_templates
    Feature record: CXX_FEATURE:1cxx_final
    Feature record: CXX_FEATURE:1cxx_func_identifier
    Feature record: CXX_FEATURE:1cxx_generalized_initializers
    Feature record: CXX_FEATURE:0cxx_generic_lambdas
    Feature record: CXX_FEATURE:1cxx_inheriting_constructors
    Feature record: CXX_FEATURE:1cxx_inline_namespaces
    Feature record: CXX_FEATURE:1cxx_lambdas
    Feature record: CXX_FEATURE:0cxx_lambda_init_captures
    Feature record: CXX_FEATURE:1cxx_local_type_template_args
    Feature record: CXX_FEATURE:1cxx_long_long_type
    Feature record: CXX_FEATURE:1cxx_noexcept
    Feature record: CXX_FEATURE:1cxx_nonstatic_member_init
    Feature record: CXX_FEATURE:1cxx_nullptr
    Feature record: CXX_FEATURE:1cxx_override
    Feature record: CXX_FEATURE:1cxx_range_for
    Feature record: CXX_FEATURE:1cxx_raw_string_literals
    Feature record: CXX_FEATURE:1cxx_reference_qualified_functions
    Feature record: CXX_FEATURE:0cxx_relaxed_constexpr
    Feature record: CXX_FEATURE:0cxx_return_type_deduction
    Feature record: CXX_FEATURE:1cxx_right_angle_brackets
    Feature record: CXX_FEATURE:1cxx_rvalue_references
    Feature record: CXX_FEATURE:1cxx_sizeof_member
    Feature record: CXX_FEATURE:1cxx_static_assert
    Feature record: CXX_FEATURE:1cxx_strong_enums
    Feature record: CXX_FEATURE:1cxx_template_template_parameters
    Feature record: CXX_FEATURE:1cxx_thread_local
    Feature record: CXX_FEATURE:1cxx_trailing_return_types
    Feature record: CXX_FEATURE:1cxx_unicode_literals
    Feature record: CXX_FEATURE:1cxx_uniform_initialization
    Feature record: CXX_FEATURE:1cxx_unrestricted_unions
    Feature record: CXX_FEATURE:1cxx_user_literals
    Feature record: CXX_FEATURE:0cxx_variable_templates
    Feature record: CXX_FEATURE:1cxx_variadic_macros
    Feature record: CXX_FEATURE:1cxx_variadic_templates


Detecting CXX [-std=c++98] compiler features compiled with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_f957e/fast 
/usr/bin/make -f CMakeFiles/cmTC_f957e.dir/build.make CMakeFiles/cmTC_f957e.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building CXX object CMakeFiles/cmTC_f957e.dir/feature_tests.cxx.o
/usr/bin/c++    -std=c++98 -o CMakeFiles/cmTC_f957e.dir/feature_tests.cxx.o -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/feature_tests.cxx
Linking CXX executable cmTC_f957e
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_f957e.dir/link.txt --verbose=1
/usr/bin/c++       CMakeFiles/cmTC_f957e.dir/feature_tests.cxx.o  -o cmTC_f957e 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


    Feature record: CXX_FEATURE:0cxx_aggregate_default_initializers
    Feature record: CXX_FEATURE:0cxx_alias_templates
    Feature record: CXX_FEATURE:0cxx_alignas
    Feature record: CXX_FEATURE:0cxx_alignof
    Feature record: CXX_FEATURE:0cxx_attributes
    Feature record: CXX_FEATURE:0cxx_attribute_deprecated
    Feature record: CXX_FEATURE:0cxx_auto_type
    Feature record: CXX_FEATURE:0cxx_binary_literals
    Feature record: CXX_FEATURE:0cxx_constexpr
    Feature record: CXX_FEATURE:0cxx_contextual_conversions
    Feature record: CXX_FEATURE:0cxx_decltype
    Feature record: CXX_FEATURE:0cxx_decltype_auto
    Feature record: CXX_FEATURE:0cxx_decltype_incomplete_return_types
    Feature record: CXX_FEATURE:0cxx_default_function_template_args
    Feature record: CXX_FEATURE:0cxx_defaulted_functions
    Feature record: CXX_FEATURE:0cxx_defaulted_move_initializers
    Feature record: CXX_FEATURE:0cxx_delegating_constructors
    Feature record: CXX_FEATURE:0cxx_deleted_functions
    Feature record: CXX_FEATURE:0cxx_digit_separators
    Feature record: CXX_FEATURE:0cxx_enum_forward_declarations
    Feature record: CXX_FEATURE:0cxx_explicit_conversions
    Feature record: CXX_FEATURE:0cxx_extended_friend_declarations
    Feature record: CXX_FEATURE:0cxx_extern_templates
    Feature record: CXX_FEATURE:0cxx_final
    Feature record: CXX_FEATURE:0cxx_func_identifier
    Feature record: CXX_FEATURE:0cxx_generalized_initializers
    Feature record: CXX_FEATURE:0cxx_generic_lambdas
    Feature record: CXX_FEATURE:0cxx_inheriting_constructors
    Feature record: CXX_FEATURE:0cxx_inline_namespaces
    Feature record: CXX_FEATURE:0cxx_lambdas
    Feature record: CXX_FEATURE:0cxx_lambda_init_captures
    Feature record: CXX_FEATURE:0cxx_local_type_template_args
    Feature record: CXX_FEATURE:0cxx_long_long_type
    Feature record: CXX_FEATURE:0cxx_noexcept
    Feature record: CXX_FEATURE:0cxx_nonstatic_member_init
    Feature record: CXX_FEATURE:0cxx_nullptr
    Feature record: CXX_FEATURE:0cxx_override
    Feature record: CXX_FEATURE:0cxx_range_for
    Feature record: CXX_FEATURE:0cxx_raw_string_literals
    Feature record: CXX_FEATURE:0cxx_reference_qualified_functions
    Feature record: CXX_FEATURE:0cxx_relaxed_constexpr
    Feature record: CXX_FEATURE:0cxx_return_type_deduction
    Feature record: CXX_FEATURE:0cxx_right_angle_brackets
    Feature record: CXX_FEATURE:0cxx_rvalue_references
    Feature record: CXX_FEATURE:0cxx_sizeof_member
    Feature record: CXX_FEATURE:0cxx_static_assert
    Feature record: CXX_FEATURE:0cxx_strong_enums
    Feature record: CXX_FEATURE:1cxx_template_template_parameters
    Feature record: CXX_FEATURE:0cxx_thread_local
    Feature record: CXX_FEATURE:0cxx_trailing_return_types
    Feature record: CXX_FEATURE:0cxx_unicode_literals
    Feature record: CXX_FEATURE:0cxx_uniform_initialization
    Feature record: CXX_FEATURE:0cxx_unrestricted_unions
    Feature record: CXX_FEATURE:0cxx_user_literals
    Feature record: CXX_FEATURE:0cxx_variable_templates
    Feature record: CXX_FEATURE:0cxx_variadic_macros
    Feature record: CXX_FEATURE:0cxx_variadic_templates
Determining if the include file pthread.h exists passed with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_8b610/fast 
/usr/bin/make -f CMakeFiles/cmTC_8b610.dir/build.make CMakeFiles/cmTC_8b610.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_8b610.dir/CheckIncludeFile.c.o
/usr/bin/cc    -o CMakeFiles/cmTC_8b610.dir/CheckIncludeFile.c.o   -c /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp/CheckIncludeFile.c
Linking C executable cmTC_8b610
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_8b610.dir/link.txt --verbose=1
/usr/bin/cc      CMakeFiles/cmTC_8b610.dir/CheckIncludeFile.c.o  -o cmTC_8b610 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”


Determining if the function pthread_create exists in the pthread passed with the following output:
Change Dir: /media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp

Run Build Command(s):/usr/bin/make cmTC_ee45c/fast 
/usr/bin/make -f CMakeFiles/cmTC_ee45c.dir/build.make CMakeFiles/cmTC_ee45c.dir/build
make[1]: 进入目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”
Building C object CMakeFiles/cmTC_ee45c.dir/CheckFunctionExists.c.o
/usr/bin/cc   -DCHECK_FUNCTION_EXISTS=pthread_create   -o CMakeFiles/cmTC_ee45c.dir/CheckFunctionExists.c.o   -c /media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/share/cmake-3.14/Modules/CheckFunctionExists.c
Linking C executable cmTC_ee45c
/media/wangbin/36005E93005E59C7/CLion-2019.2/clion-2019.2/bin/cmake/linux/bin/cmake -E cmake_link_script CMakeFiles/cmTC_ee45c.dir/link.txt --verbose=1
/usr/bin/cc  -DCHECK_FUNCTION_EXISTS=pthread_create    CMakeFiles/cmTC_ee45c.dir/CheckFunctionExists.c.o  -o cmTC_ee45c -lpthread 
make[1]: 离开目录“/media/wangbin/36005E93005E59C7/tlpl/cmake-build-debug/CMakeFiles/CMakeTmp”

