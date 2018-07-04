---
title: Hadoop Datanode Service
---

{% capture overview %}

{% endcapture %}

The Hadoop service will simulate a hadoop database. Currently configured for the following querry :
  -/jmx?qry=Hadoop:service=DataNode,name=DataNodeInfo
  -/jmx?qry=Hadoop:service=NameNode,name=FSNamesystemState

```
[service.hadoop_datanode]
type="hadoop_datanode"

[[port]]
port="tcp/50075"
services=["hadoop_datanode"]

```
