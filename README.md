GITstrAPT
=========

Runtime bootstrapping of virtual, paravirtual, and bare metal machinery.

This will be eventually packaged as .rpm and .deb, for now.. here is how you can use
curl on a Debian based system:

apt-get -y install curl && curl http://gitstrapped.elasticprovisioner.com/install-gitstrapped-2012071301 | bash

It will run an installation script. From that point on you can use
ep-gitstrapped <strap>