# SIP#1.00: Decentralized, Censorship-Resistant, Lightweight Blockchain With Security For Securing Address Space And Other Properties

This project is named "TransparencyChain" for creating a truly, decentralized, transparent Web 3.0 space seperate from existing types.

## What it stores on chain

### ALMAC ADDRESS

The ALMAC ADDRESS as an identifier is stored on chain in 512 array blocks. It uses minipow to achieve spam protection.

For the validating nodes, a hash table is used to check for unique addresses and whether to add them to the chain.

### LATEST BLOCK UPDATE

The latest block update is one that serves to keep up with latest blocks. The block number is stored in a unique way for the Block Lattice "Sumatra".

- [ ] Lattice ID Number
  - [ ] Latest In Lattice (ex. 1..2..3..4..5)
  - [ ] Position In ALMAC Storage (by 512 block number)
  - [ ] Exact Position In ALMAC Storage (ordered by the block with hash check)
- [ ] Tx Block Number
  - [ ] A Tx Block Number is a confirmation made on chain 


