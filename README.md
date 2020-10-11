
# Personal GDB mirror

This is a versioned snapshot of the GDB source code, starting with 
[GDB 9.2](https://ftp.gnu.org/gnu/gdb/gdb-9.2.tar.gz). 

The complete GDB source tree is located under the `src` directory.

## Quick build steps

```shell
mkdir build-release && cd build-release
../src/configure --prefix=~/.local --enable-tui
make -j8
make install
```

## Resources

- [Official GDB home](https://www.gnu.org/software/gdb/)
- [Installing GDB](https://sourceware.org/gdb/current/onlinedocs/gdb/Installing-GDB.html)
- [Building GDB guide](http://www.linuxfromscratch.org/blfs/view/svn/general/gdb.html)

