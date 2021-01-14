# Inventory

## Garbage Collection

Inventory needs to clean garbages which are not exist, such as deleted server.

There are two types of garbage collection in the inventory service.

1. Periodic garbage collection by inventory-scheduler
2. Run-time garbage collection after collecting data

### Architecture

![](../images/garbage_collection.png)
