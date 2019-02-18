# dotnetmentor/eventstore

Extends the docker image [eventstore/eventstore](https://hub.docker.com/r/eventstore/eventstore) with additional features, primarily used for local development.

## Image tags

We try to match the tags used by the base docker image (eventstore/eventstore).

## Additional features

### Restore

Triggers a restore of a backup located in Amazon S3 (using esutils)

```bash
./run restore
```

### Cluster

Brings up a clustered eventstore using docker-compose

```bash
./run cluster
```
