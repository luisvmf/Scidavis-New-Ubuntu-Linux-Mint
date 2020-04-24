# Scidavis-ubuntu18-mint19.2

Scidavis was removed from package manager on ubuntu 18 and derivatives.
This is a proot container with scidavis and dependencies installed that can run on ubuntu 18 and derivatives.
No root needed to install or run the container, it can run from your home directory.

Tested on a clean install of ubuntu 18.04 and on linux mint 19.2. Probabily can run on other versions too.
This runs on 64bit only.

Proot is included on the tar file below. The file is very big (1G). This is not an virtual machine, so it doesn't need lots of ram memory to run. Your home directory is mounted on /home on the container. Scidavis connects directly to the Xserver on the host, the shell script distributed with the tar bellow takes care of exporting the required DISPLAY variable from the host to the container.

To run:
wget https://github.com/luisvmf/Scidavis-ubuntu18-mint19.2/releases/download/1.0.0/scidavis.tar

tar -xvf scidavis.tar

cd scidavis

./scidavis.sh

Tar may give the folowing message after finishing: "tar: Exiting with failure status due to previous errors". Just ignore if scidavis folder was created on current directory.

In case of problems with icons not showing you can change theme on scidavis in edit->preferences->style
