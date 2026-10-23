---
topic:
  - Technology
---
A blockchain is a distributed ledger[^1] completely open to anyone, definitive and immutable. It accumulates growing lists of records that are securely linked together via cryptographic hashes

Each block contains (at least)
- a cryptographic hash of the previous block
- a hash or timestamp - an unique sequence of numbers and letters that identify the data of the block, which means that a change on the data results in a change on the hash
- transaction data

*Since each block contains information about the previous block, they effectively form a chain, with each additional block linking to the ones before it. Consequently, blockchain transactions are irreversible in that, once they are recorded, the data in any given block cannot be altered retroactively without altering all subsequent blocks* [^2]

![[Media/Blockchain|700]]

# History

The Blockchain technique was described by a group of researchers in 1991 with the goal of timestamping digital documents so it's was not possible to backdate them or to tamper with them

Only in 2009 that Satoshi Nakamoto adapted the technique to be used with bitcoin

# Security

Changing a block would require a change of the hash of all blocks of the sequence, a redo of the proof-of-work for each block and to take control of more than 50% of the peer-to-peer network

## Hash sequence

If someone tampers the data of a block, its hash changes and the sequence becomes invalid. It would be necessary to change every other block in the sequence

## Proof-of-work

A mechanism that slows down the creation of new blocks

## Decentralization

There's no central entity managing the chain. It's completely distributed using a peer-to-peer network. Each user on the network has a copy of the sequence. Every time a block is added, each node from each user verifies the block. If everything checks out, then there's consensus on the valid blocks

# Privacy

Most blockchains make it easy to track users transactions. This could be a problem for [[Digital privacy]]


[^1]: A ledger is a book or collection of accounts in which accounting transactions are recorded