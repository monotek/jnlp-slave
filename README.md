# jnlp-slave with docker-ce and support for arm docker containers

## run via:

* docker run --privileged -ti -v /run/docker.sock:/run/docker.sock monotek/jnlp-slave

## to run arm docker contrainer inside:

* docker run -v /usr/bin/qemu-arm-static:/usr/bin/qemu-arm-static armbuild/debian uname -a
