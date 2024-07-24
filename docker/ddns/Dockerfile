FROM golang:1.23rc2-alpine3.20

# Q: What is this?
# A: DDNS is a personal DynDNS client for DigitalOcean, see https://github.com/skibish/ddns.

RUN go install github.com/skibish/ddns@latest

CMD ["ddns", "-conf-file", "/config/ddns.yml"]