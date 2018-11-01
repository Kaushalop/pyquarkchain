### TPS Competition Questionnaire

*Please replace the square brackets and the text in it with your answers*

**Number of CPUs**

96 vCPUs

**Memory (GB)**

86.4GB

**Storage (GB)**

8GB

**Network**

[Comment on the network connecting clusters. For example, 1 Gbps LAN]

**Machine Type (Optional)**

GC - Kubernetes Engine - n1-highcpu-96

**Command Lines for Running Cluster**
```
pypy3 multi_cluster.py --num_clusters=3 --mine --devp2p_enable
curl -X POST --data '{"jsonrpc":"2.0","method":"createTransactions","params":{"numTxPerShard":10000, "xShardPercent":10},"id":0}' http://localhost:38491

```

**Peak TPS**

3323.37

**Video URL**

https://youtu.be/DCyDm16dovo

**Output From `stats` Tool**
```
[Copy the complete output from `stats` here. It should capture the cluster configuration and at least 10 minute continuous samples (60 rows) with at least one sample showing the TPS claimed above.]
```

**Additional Comment**


