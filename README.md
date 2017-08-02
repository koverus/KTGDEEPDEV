# KTGDEEPDEV
Ubuntu GPU Dev Box for NVIDIA Jetson AI


Configuration for my Docker machines

Defines machines for docker-machine and their
compose files, while integrating the two via a small
shell script.

Machine definitions:
A directory structure is expected as follows:

<machine-name>/machine.env
<machine-naem>/docker-compose.yml

The machine.env file accepts any environment variable
known for running docker-machine commands (see docker-machine create --help).

Special environment variables for docker-machine:
MACHINE_DRIVER for specifying the driver to use with machine.

MACHINE_GENERIC_IP_ADDRESS for configuring
generic machines, as machine itself does not support a variable for this.

Using Docker image:
This utility can be self-hosting on Docker.

From a directory containing machine definitions:

$ docker run -v $PWD:/machines ewindisch/machine-compose
