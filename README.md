# Go LB
[![Build Status](https://travis-ci.org/onestraw/golb.svg?branch=master)](https://travis-ci.org/onestraw/golb)
[![Coverage Status](https://coveralls.io/repos/github/onestraw/golb/badge.svg?branch=master)](https://coveralls.io/github/onestraw/golb?branch=master)
[![godoc](https://godoc.org/github.com/onestraw/golb?status.svg)](https://godoc.org/github.com/onestraw/golb)

Yet another load balancer
![golb](golb.png)

## Features

- [roundrobin](roundrobin/): smooth weighted roundrobin method
- [chash](chash/): cosistent hashing method
- [balancer](balancer/): **multiple LB instances, passive health check, SSL offloading**
- [controller](controller/): dynamic configuration, **REST API to start/stop/add/remove LB at runtime**
- [service discovery](discovery/): autodiscover backend services with **etcd**
- [statistics](stats/): HTTP method/path/code/bytes

## Examples

- [Basic configuration and REST API](examples/restapi)
- [SSL offloading](examples/https)
- [Service discovery with etcd](examples/sdserver)

## LICENSE

MIT License

Copyright (c) 2018 Larry He
