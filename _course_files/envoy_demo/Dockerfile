FROM envoyproxy/envoy:v1.16.4
RUN apt-get update
COPY config.yaml /etc/envoy.yaml
CMD /usr/local/bin/envoy -c /etc/envoy.yaml
