cloud-init-docker-build
=======================

Build cloud-init for supported distros with docker scripts + makefiles.

Usage
-----

```bash
# required: linux install with internet and recent-ish docker installed
git clone https://github.com/jayofdoom/cloud-init-docker-build
cd cloud-init-docker-build/$distro
make
```

TODO
----

- Debian 7 builder doesn't work yet due to missing requirement python-jsonpatch
- Root-level Makefile that will build all packages
- Makefile targets to upload packages to Cloud Files CDN
