## Memcached replication and failover with mcrouter
This is an example helm chart for memcached with mcrouter frontend. It provides replicated cache writes along with read miss failover thus some sort of redundancy is acheived.

[werf](https://werf.io/) tool is used to assemble mcrouter container and publish whole chart to kubernetes cluster.
