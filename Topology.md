```mermaid


graph TB
LB[Load Balancer]
App1[App Server 1]
App2[App Server 2]
DB1[DB Server 1]
DB2[DB Server 2]
DB3[DB Server 3]

click App1 callback "tpamulapp01"
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
eyJoaXN0b3J5IjpbNDA3MDI5MTgyLDE1MjYxODU0MjUsMjEzNz
UwNzkzOCwtMjg1OTI4NjU2LDcyNTk3NzEyOF19
-->