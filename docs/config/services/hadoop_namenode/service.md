---
title: Hadoop NameNode Service
---

{% capture overview %}

{% endcapture %}

The Hadoop service will simulate a hadoop database. Currently configured for the following querry :
  -/jmx?qry=Hadoop:service=NameNode,name=NameNodeInfo
  -/jmx?qry=Hadoop:service=NameNode,name=FSNamesystemState

```
[service.hadoop_namenode]
type="hadoop_namenode"

[[port]]
port="tcp/50070"
services=["hadoop_namenode"]

```
