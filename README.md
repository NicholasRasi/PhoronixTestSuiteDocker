# phoronix-test-suite-docker

This repository contains different Dockerfiles with [Phoronix Test Suite](https://www.phoronix-test-suite.com/) and a set of [benchmarks](https://openbenchmarking.org/) already installed.

### Cloud
```
phoronix-test-suite run cloud
```

#### Database
- [pts/sqlite](https://openbenchmarking.org/test/pts/sqlite)
- [pts/redis](https://openbenchmarking.org/test/pts/redis)
- [pts/cassandra](https://openbenchmarking.org/test/pts/cassandra)

#### Server
- [pts/apache](https://openbenchmarking.org/test/pts/apache)
- [pts/nginx](https://openbenchmarking.org/test/pts/nginx)
- [pts/blogbench](https://openbenchmarking.org/test/pts/blogbench)

### Hardware
```
phoronix-test-suite run hardware
```

### System Test
- [pts/osbench](https://openbenchmarking.org/test/pts/osbench)
- [pts/pybench](https://openbenchmarking.org/test/pts/pybench)

#### Disk
- [pts/tiobench](https://openbenchmarking.org/test/pts/tiobench)

#### Memory
- [pts/ramspeed](https://openbenchmarking.org/test/pts/ramspeed)

#### Processor
- [pts/compress-7zip](https://openbenchmarking.org/test/pts/compress-7zip)
- [pts/openssl](https://openbenchmarking.org/test/pts/openssl)

#### Network
- [pts/sockperf](https://openbenchmarking.org/test/pts/sockperf)