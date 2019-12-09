FROM ubuntu

ADD healthcheck.sh /

HEALTHCHECK --interval=1s --timeout=1s CMD ./healthcheck.sh
