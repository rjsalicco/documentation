# Server Topology

```mermaid
graph TB

LB(F5 Load Balancer)
APP1(Application Server 1)
APP2(Application Server 2)
DB1(Database Server 1)
DB2(Database Server 2)
LB --> APP1
LB --> APP2
APP1 --> DB1
APP1 --> DB2
APP2 --> DB1
APP2 --> DB2
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNTY5MDU4OV19
-->