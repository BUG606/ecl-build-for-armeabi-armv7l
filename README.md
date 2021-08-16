# ecl-build-for-armeabi-armv7l

## ecl(Embeddable Common-Lisp)
You can run this program in termux.
Visit https://gitlab.com/embeddable-common-lisp/ecl to get source code.

Here (https://github.com/plops/ecl-termux-binary) are more infomation
Running these to build ecl:

```Shell
git clone https://gitlab.com/embeddable-common-lisp/ecl.git
cd ecl
./configure --prefix=$PREFIX --build=arm-linux-androideabi --enable-gmp
make -j9
make install
```
ecl version :21.2.1
