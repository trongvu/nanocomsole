
Cross-build through the Android NDK
-----------------------------------

Install Android NDK and set environment variables needed for cross-compilation
through it.
Reference:
https://github.com/marco-pratesi/android/blob/master/00_NOTES-env_for_cross_compiling.txt
In particular, to build Nanocomsole, you only need to set the CC and STRIP
environment variables.

Then unpack sources, change directory to the source tree,
and build through "make": as an example,
tar xf nanocomsole-[...].tar.gz ; cd nanocomsole-[...]
make -e


Native build through a native GCC for Android
---------------------------------------------

Nanocomsole can also be easily compiled through a native GCC for Android:
see https://github.com/marco-pratesi/android/tree/master/gcc_and_friends .
Just set CC=gcc and run make.

