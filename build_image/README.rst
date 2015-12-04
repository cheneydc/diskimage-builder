Build image for trove
=========================

Variables in ``trove_env`` should be sepecified according to your own evnironment.
After set the variables, run ``ubuntu14.04-x64-trove`` to build the image.

A database type should be sepcified when build a image::

    $ ./ubuntu14.04-x64-trove [mysql|percona|pxc]
