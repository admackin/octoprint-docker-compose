FROM octoprint/octoprint

RUN apt-get install -y iproute2

COPY set-host-and-run /

ENTRYPOINT ["/set-host-and-run", "/init"]
