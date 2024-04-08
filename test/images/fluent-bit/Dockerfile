# Fluent Bit Dockerfile
FROM fluent/fluent-bit:1.8

# Custom configurations here
COPY fluent-bit.conf /fluent-bit/etc/
COPY parsers.conf /fluent-bit/etc/

CMD ["/fluent-bit/bin/fluent-bit", "-c", "/fluent-bit/etc/fluent-bit.conf"]
