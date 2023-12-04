# Distributed data storage key characteristics

## **Availability**

- High availability for reads

  - Sloppy Quorum
  - Hinted Hand-off

- High availability for writes

  - Vector clocks

## **Scalability**

- Replication

- Partitioning

  - Consistent hashing

## **Fault Tolerance**

- Replication

## **Failure**

- Temporary Failures Recovery

  - Sloppy quorum
  - Hinted hand-off

- Permanent Failures Recovery

  - Merkle trees
    (Anti-entropy)

- Membership and
  Failure Detection

  - Gossip Protocol

## **Consistency**

- Data conflict resolution

## **Always Writable Experience**

- Hinted hand-off

## **Configure Faster Read-Write**

- Through quorum protocol

## **Anti-entropy**

- Merkle trees

## **Nodes peer-to-peer communication**

- Gossip protocol
