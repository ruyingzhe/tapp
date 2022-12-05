From alpine:3.9

RUN mkdir /etc/certs
ADD ca.crt /etc/certs
ADD tls.crt /etc/certs
ADD tls.key /etc/certs

ENTRYPOINT ["sleep 3600s"]
