Bootstrap: docker
From: ubuntu:18.04

%labels
MAINTAINER darachm

%help

    This container is for providing `bartender` for some bioinformatic pipelines.
    
%post

    apt-get -y update
    apt-get -y install gcc-4.8 git make g++
    git clone https://github.com/LaoZZZZZ/bartender-1.1.git
    cd bartender-1.1
    make all
    sudo make install

%test

    # ?
