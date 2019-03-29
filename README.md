# ANSIBLE on CentOS (with SSHD)

Docker Image with SSHD.

The build of this project you can download as:

`` docker pull toolstodevops/centos-ansible:latest ``

For use, see example to Dockerfile:

FROM ansible:latest
WORKDIR /opt
COPY <directory> .
RUN ansible-playbook <path_main>.yaml