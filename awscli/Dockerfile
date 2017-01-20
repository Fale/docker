FROM fedora:latest
MAINTAINER Fabio Alessandro Locati <me@fale.io>

RUN dnf -y install awscli && dnf -y update; dnf clean all

ENTRYPOINT [ "aws" ]
