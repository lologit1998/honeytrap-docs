---
title: Redis Service
---

{% capture overview %}

{% endcapture %}

The Redis service will simulate a redis server. Currently the INFO command has been implemented.

```
[service.redis]
type="redis"
version="4.0.6"
os="Ubuntu"

[[port]]
port="tcp/6379"
services=["redis"]

```
