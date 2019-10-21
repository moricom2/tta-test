## Custom Dockerfile
FROM consol/centos-xfce-vnc
ENV REFRESHED_AT 2019-10-21

# Switch to root user to install additional software
USER 0

## Install a git
RUN yum install -y git \
    && yum clean all

## switch back to default user
USER 1000
