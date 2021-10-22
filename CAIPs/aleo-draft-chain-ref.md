---
caip: <to be assigned>
title: Blockchain Reference for the Aleo Namespace
author: Charles E. Lehner (@clehner)
discussions-to: [https://github.com/ChainAgnostic/CAIPs/pull/36]
status: Draft
type: Standard
created: 2021-10-22
updated: 2021-10-22
requires: 2
---

## Simple Summary

This document is about the details of the Aleo namespaces and references for CAIP-2.

## Abstract

In CAIP-2 a general blockchain identification scheme is defined. This is the
implementation of CAIP-2 for Aleo.

## Motivation

See CAIP-2.

## Specification

### Aleo Namespace

The namespace "aleo" refers to the Aleo open-source blockchain platform.

#### Reference Definition

The network (chain) identifier is a single byte, an unsigned integer, as
documented here:
  https://developer.aleo.org/aleo/concepts/transactions#network-id

For CAIP-2 purposes, the network id byte is represented in decimal.

The mainnet network ID is `0`.

## Rationale

Blockchains in the "aleo" namespace are identified by their network ID as mentioned in the Reference Definition Section.

## Backwards Compatibility

Not applicable

## Test Cases

This is a list of manually composed examples

```
# Aleo Mainnet
aleo:0
```

## Links

- [Implementation](https://github.com/AleoHQ/snarkOS/blob/22eb75bbf682c6f8d215a5e20b56b7a8a45b87be/snarkos/display.rs#L93-L96)

## Copyright

Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).
