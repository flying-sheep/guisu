guisu
=====

DE independent graphical sudo

Current resources:

* [gsmartcontrol](https://github.com/freenas/freenas/blob/master/src/pcbsd/pc-extractoverlay/ports-overlay/usr/local/bin/gsmartcontrol-root) supports many graphical sudo options (but [pc-su](https://github.com/trueos/pcbsd/blob/fec6e46bee2471c6eb2c2df901452256e9139d95/src-sh/pcbsd-utils/pc-su/pc-su) is itself a wrapper)
* [rosa-imagewriter](https://abf.io/soft/rosa-imagewriter/blob/master/platform_lin_suprogram.cpp) detects more DEs
* [`sudo ENV="$ENV" ... "$@"`](http://unix.stackexchange.com/a/2960/15057) can be used as fallback
