FROM fedora:latest
MAINTAINER Fabio Alessandro Locati <me@fale.io>

RUN dnf -y install aws-shell && dnf -y update; dnf clean all

ENTRYPOINT [ "aws-shell" ]
