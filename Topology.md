```mermaid
graph TB
LB[Load Balancer]
App1[App Server 1]
App2[App Server 2]
DB1[DB Server 1]
DB2[DB Server 2]
DB3[DB Server 3]

click App1 alert "tpamulapp01"
click App2 callback "tpamulapp02"

LB --> App1
LB --> App2
App1 --> DB1
App1 --> DB2
App1 --> DB3
App2 --> DB1
App2 --> DB2
App2 --> DB3
```
<!--stackedit_data:
eyJoaXN0b3J5IjpbODIzMDIzODc5LDIxMzc1MDc5MzgsLTI4NT
kyODY1Niw3MjU5NzcxMjhdfQ==
-->