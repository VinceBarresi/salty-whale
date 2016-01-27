# build from ubuntu 14.04
FROM ubuntu:trusty

# update apt
RUN sudo apt-get update

# install git
RUN sudo apt-get install -y git-all

# install wget
RUN sudo apt-get install wget

# install salt master
RUN sudo apt-get install -y salt-master

# restart salt minion
CMD sudo restart salt-master