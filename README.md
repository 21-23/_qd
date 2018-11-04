# qd platform

There is a `Makefile` to help you work with qd-platform:

To build Docker image:

    $ make build

To run platform:

    $ make run

This will run platform container, which will be removed automatically after you stop it.
You can use usual `docker stop` or `docker restart` to handle this container.

By default, `$ make` will build and run the platform.
