# web-coming-soon
Temporary static landing page until the rest of the site is developed and at least one app is written.

## Build/test locally

```shell script
./gradlew test distZip
unzip build/distributions/Example.zip
Example/bin/Example
```

then:
```shell script
curl -v http://localhost:8080/
```

## Build/run in Docker

```shell script
./build_and_run.sh
```

then:
```shell script
curl -v http://localhost:8080/
```

## Attribution
* [http4k/examples](https://github.com/http4k/examples) for basic template