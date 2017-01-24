FROM fedora:latest
MAINTAINER Fabio Alessandro Locati <me@fale.io>

RUN dnf -y install perl-Encode weechat && dnf -y update; dnf clean all

ENTRYPOINT [ "weechat" ]
