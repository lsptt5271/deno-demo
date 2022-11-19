ARG DENO_VERSION=1.27.2

FROM denoland/deno:bin-$DENO_VERSION AS deno
FROM ubuntu
COPY --from=deno /deno /usr/local/bin/deno