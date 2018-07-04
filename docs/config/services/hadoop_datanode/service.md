---
title: Hadoop Datanode Service
---

{% capture overview %}

{% endcapture %}

The Hadoop service will simulate a hadoop database.

```
[service.hadoop_datanode]
type="hadoop_datanode"
version="2.7.1"
os="Ubuntu"

[[port]]
port="tcp/50075"
services=["hadoop_datanode"]

```
