Just. a simple docker image to run basic tests against a psql server.

# How to run?

```
docker run -it \
    -e "DB_DATABASE=profile" \
    -e "DB_USER=profile" \
    -e "DB_PASSWORD=profile" \
    -e "DB_HOST=dbhost" \
    -e "DB_PORT=dbhost" \
    -e "FILL_FACTOR=100" \
    -e "SCALE_FACTOR=100" \
    -e "nproc=4" \
    pgbench
```
