# Bytes.co Alpine envsubst

A no-frills Alpine envsubst container. Currently based on Alpine 3.17.

## Example Usage
```bash
docker run --rm -i -e "HOME=$HOME" bytesco/envsubst < ./input.txt > output.txt
```

## Tags
- [latest](https://github.com/BytesCo/docker-envsubst/blob/main/Dockerfile)
