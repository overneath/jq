# Nothin' but JQ

![./jq][jq-png]

## But Why Though

I needed a minimal, standalone installation of [stedolang/jq][jq-src] in a Docker image to serve as a simple, containerized installation source.

## Docker

To install into an image via `Dockerfile`:

```dockerfile
COPY --from=overneath/jq:1.6 /opt/local/ /usr/local/
```

---

[jq-png]: https://github.com/stedolan/jq/raw/63a2b85883be8850e418c5dbb64e05d115abc00b/jq.png "./jq"
[jq-src]: https://github.com/stedolan/jq "JQ on Github"
