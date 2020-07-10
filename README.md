# TxChain: compressed-inclusion-proofs

Repository with the source code for

TxChain: Efficient Cryptocurrency Light Clients viaContingent Transaction Aggregation

This repository contains

* `txchain-relay` - a Bitcoin SPV client Ethereum, implementing compressed inclusion proofs as defined in TxChain
* `data-generator` - a Bitcoin data generator
* `go-ethereum` - a fork of Go Ethereum containing `TXEXISTS`
* `solidity` - a fork of solidity containing `TXEXISTS`

The `txchain-relay` also contains [a contract](./txchain-relay/contracts/TxChecker.sol) leveraging our proposed `TXEXISTS` instruction to efficiently verify the inclusion of previous transactions in Ethereum.
