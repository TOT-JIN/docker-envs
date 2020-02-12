#####################################################################
# Dockerfile to build IntelliJIDEALicenseServer Running Containers  #
# Based on Ubuntu                                                   #
#####################################################################
# Set the base image to Ubuntu
FROM ubuntu
# File Author / Maintainer
MAINTAINER zhanjie.jin i@zhanjie.me
COPY src/IntelliJIDEALicenseServer_linux_amd64 /usr/local/sbin/IntelliJIDEALicenseServer
RUN chmod a+x /usr/local/sbin/IntelliJIDEALicenseServer
EXPOSE 1027
ENTRYPOINT ["/usr/local/sbin/IntelliJIDEALicenseServer","-p","1027","-u","zhanjie.me"]
