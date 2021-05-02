# PGBouncer-rr

PGBouncer-rr is a patch from [AWS](https://github.com/awslabs/pgbouncer-rr-patch) of the awesome PGBouncer.
It allows routing and rewriting of queries via Python hooks.

This repo build on [this work](https://github.com/riceo/docker-pgbouncer-rr) to obtain a docker image for PGBouncer-rr v1.12;

The image requires a `pgbouncer.conf` mounted at `/etc/pgbouncer-rr`
