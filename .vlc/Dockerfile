# Version: 0.3
FROM centos:centos7
MAINTAINER Anton Bugreev <anton@bugreev.ru>

## repo
RUN rpm -Uvh http://dl.fedoraproject.org/pub/epel/7/x86_64/e/epel-release-7-5.noarch.rpm
RUN rpm -Uvh http://li.nux.ro/download/nux/dextop/el7/x86_64/nux-dextop-release-0-1.el7.nux.noarch.rpm

## install vlc
RUN yum install vlc-core -y

## add user for running vlc
RUN useradd vlc -u 1000

## Main
USER vlc
WORKDIR /home/vlc

## allow ports
EXPOSE 8094

