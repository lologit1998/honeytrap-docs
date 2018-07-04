---
title: Hadoop NameNode Service
---

{% capture overview %}

{% endcapture %}

The Hadoop service will simulate a hadoop database.

```
[service.hadoop_namenode]
type="hadoop_namenode"
version="2.7.1"
os="Ubuntu"

[[port]]
port="tcp/50070"
services=["hadoop_namenode"]

```
