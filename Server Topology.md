# Server Topology

```mermaid
graph TB

LB(F5 Load Balancer)
APP1(Application Server 1)
APP2(Application Server 2)
DBS1(Database Server 1)
DBS2(Database Server 2)
LB --> APP1
LB --> APP2
APP1 --> DBS1
APP1 --> DBS2
APP2 --> DBS1
APP2 --> DBS2
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4MzI5MDE2OTddfQ==
-->