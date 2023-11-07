FROM registry.suse.com/bci/bci-base:15.4

RUN zypper -n install git && \
    rm -rf /var/cache/zypp/*

COPY bin /usr/local/sbin/

VOLUME /usr/local/sbin

CMD ["fibonacci"]
