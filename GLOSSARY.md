# Systems Engineering Glossary: Distributed Pub/Sub Broker Core

### Commit Log
Append-only physical record of ordered messages partitioned by topic.

### Consumer Group
Set of subscribers coordinating partition leases to consume messages in parallel without duplication.

### Zero-Copy Streaming
Transferring byte segments directly from disk cache to the network socket descriptor without userspace memory buffering.

### Partition Offset
Sequential integer uniquely identifying the position of each message within a specific topic partition.
