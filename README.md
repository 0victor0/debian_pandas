#Debian + pandas on Docker

Debian and pandas are two great tastes to go great together. They just take
forever to build from scratch, so here is this base image. Planning to push new builds as new
versions of Debian and pandas are released.



You can mount your host's current directory into Docker with this command:

        docker -it --rm -v $(pwd):/pandas victorclark/debian_pandas:latest
