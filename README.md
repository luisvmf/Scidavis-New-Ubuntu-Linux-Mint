# Scidavis-ubuntu18-mint19.2

Scidavis was removed from package manager on ubuntu18 and derivatives.
This is a proot container with scidavis and dependencies installed that can run on ubuntu18 and derivatives.
No root needed to install or run the container, it can run from your home directory.

Tested on a clean install of ubuntu 18.04 and on linux mint 19.2. Probabily can run on other versions too.
This runs on 64bit only.

To run:
wget https://github.com/luisvmf/Scidavis-ubuntu18-mint19.2/releases/download/1.0.0/scidavis.tar

tar -xvf scidavis.tar (may give an error, just ignore if scidavis folder is created)

cd scidavis

./scidavis.sh
