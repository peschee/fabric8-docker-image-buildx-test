# [docker-maven-plugin] Test Repo

## Run with

```shell
$ mvn clean install
$ docker run --rm com.inventage.test.fabric8-docker-image-buildx-test:latest
```

## Fail with

If you're on `amd64`, run

```shell
$ mvn clean install -Ddocker.platforms=linux/arm64
```

If you're on `arm64`, run

```shell
$ mvn clean install -Ddocker.platforms=linux/amd64
```

[docker-maven-plugin]: https://github.com/fabric8io/docker-maven-plugin
