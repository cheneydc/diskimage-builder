Build image for trove
=========================
Variables in ```trove_env``` should be sepecified according to your own evnironment.
After set the variables, run ```ubuntu14.04-x64-trove``` to build the image.

    $ ./ubuntu14.04-x64-trove
    ERROR: Must specify a database type.
           Get support database types with -h.
    $ ./ubuntu14.04-x64-trove -h
    usage: get help    ./ubuntu14.04-x64-trove -h
           make image  ./ubuntu14.04-x64-trove [mysql|percona|pxc]

A database type should be sepcified when build a image:

    $ ./ubuntu14.04-x64-trove [mysql|percona|pxc]
