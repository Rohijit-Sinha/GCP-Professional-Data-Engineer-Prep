## Replication
### Read replicas
### Cross-region read replicas
### Cascading read replicas
Cascading replication lets you create a read replica under another read replica in the same or a different region.
**Disaster recovery**  
**Performance improvements**  
**Scale Reads**  
**Cost reduction**

## High Availability
A Cloud SQL instance configured for HA is also called a regional instance and has a primary and secondary zone within the configured region.  
Within a regional instance, the configuration is made up of a primary instance and a standby instance.  
Through **synchronous replication** to each zone's persistent disk, all writes made to the primary instance are replicated to disks in both zones before a transaction is reported as committed.

In the event of an instance or zone failure, the standby instance becomes the new primary instance. Users are then rerouted to the new primary instance. This process is called a failover.

If you need to have the primary instance in the zone that had the outage, you can do a failback. A failback performs the same steps as the failover, only in the opposite direction, to reroute traffic back to the original instance.