# ecl-build-for-armeabi-armv7l

As the title.
You can run this program in termux.
Visit https://gitlab.com/embeddable-common-lisp/ecl to get source code.

Running these to build ecl:

```Shell
./configure --prefix=$PREFIX --build=arm-linux-androideabi --enable-gmp
make -j9
make install
```
ecl version :21.2.1
