FROM debian:unstable-20220328-slim

RUN apt update && apt-get install -y \
  vim \
  dnsutils \
  traceroute \
  curl \
  netcat-traditional \
  postgresql-client-14 \
  jq \
  nmap \
  && rm -rf /var/lib/apt/lists/*

CMD ["/bin/sh", "-c", "trap : TERM INT; sleep 9999999999d & wait"]