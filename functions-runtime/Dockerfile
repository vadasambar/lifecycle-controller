FROM denoland/deno:1.25.3

LABEL org.opencontainers.image.source="https://github.com/keptn-sandbox/lifecycle-controller" \
    org.opencontainers.image.url="https://keptn.sh" \
    org.opencontainers.image.title="Keptn Functions Runtime" \
    org.opencontainers.image.vendor="Keptn" \
    org.opencontainers.image.licenses="Apache-2.0"

COPY entrypoint.sh /entrypoint.sh

USER deno

ENTRYPOINT /entrypoint.sh
