# propagator-docker

build with:
```bash
docker build -t propagator .
```

run with:
```bash
docker run -it -v `pwd`/work/:/work --entrypoint /bin/bash propagator
```