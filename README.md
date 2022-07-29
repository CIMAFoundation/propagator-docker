# propagator-docker

build with:
```bash
docker build -t propagator .
```

run with:
```bash
docker run -it -v `pwd`/work/:/work --entrypoint /bin/bash propagator
```

run the model inside the docker
```bash
python main.py -f ../work/params.json -veg ../work/vegAreaTest.tiff -dem ../work/demAreaTest.tiff -of ../work/output/
```
```