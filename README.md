# Dockerfiles for (un)popular fuzzers! 🐳

## Building images

At first build base image:

```
docker build -t fuzzbuntu -f fuzzbuntu-dockerfile .
```

Build and run desired fuzzer:

```
docker build -t afl -f afl-dockerfile .
# Fire!
docker run -it afl /bin/bash
```

## Fuzzers and versions

+ [AFL++](https://github.com/vanhauser-thc/AFLplusplus) (pulled from git)
+ [aflgo](https://github.com/aflgo/aflgo) (git)
+ [aflsmart](https://github.com/aflsmart/aflsmart) (git)
+ [domato](https://github.com/googleprojectzero/domato) (git)
+ [Eclipser](https://github.com/SoftSec-KAIST/Eclipser) (git)
+ [fuzzowski](https://github.com/nccgroup/fuzzowski) (git)
+ [go-fuzz](https://github.com/dvyukov/go-fuzz) (git)
+ [honggfuzz](https://github.com/google/honggfuzz) (git)
+ [javafuzz](https://github.com/fuzzitdev/javafuzz) (git)
+ [jsfuzz](https://github.com/fuzzitdev/jsfuzz) (git)
+ [LibFuzzer](https://llvm.org/docs/LibFuzzer.html) (git)
+ [neuzz](https://github.com/Dongdongshe/neuzz) (git)
+ [pythia](https://github.com/mboehme/pythia) (git)
+ [python-afl](https://github.com/jwilk/python-afl) (git)
+ [pythonfuzz](https://github.com/fuzzitdev/pythonfuzz) (git)
+ [sharpfuzz](https://github.com/Metalnem/sharpfuzz) (git)
