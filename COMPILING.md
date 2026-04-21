To compile HYPERCube, you must first prepare enet to be compiled. Change directory into ./enet/ and run
```
aclocal && automake -a -c --foreign && autoconf
./configure
```

This should prepare enet to be built by Cube's main Makefile.
Now change directory into ../src and run make. You should be done!
