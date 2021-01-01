# KDC Server Container

This container is a simplified version of [docker-kerberos](https://github.com/ist-dsi/docker-kerberos), it provides a standalone KDC server in a docker container, exposing default KDC ports: `749 TCP` and `88 UDP`. The default realm is `EXAMPLE.COM`. Additionally, a default KDC admin principal `kadmin/admin@EXAMPLE.COM` and a no permissions principal are setup `noPermissions@EXAMPLE.COM`, these may be used for KDC functionality testing such as `kadmin` commands. For a more KDC admin focused scenario, see [this docker kerberos project](https://github.com/ist-dsi/docker-kerberos).

## Starting

From the container directory, use `docker-compose up` to start the KDC server. The output will stop when the container starts runnning.

