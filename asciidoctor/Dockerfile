FROM fedora:latest
MAINTAINER Fabio Alessandro Locati <me@fale.io>

RUN dnf -y install \
    liberation-fonts \
    rubygem-asciidoctor-pdf \
    && dnf -y update; dnf clean all

WORKDIR /documents
VOLUME /documents

CMD ["/bin/bash"]
