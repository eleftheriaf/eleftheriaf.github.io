---
title: "Bandwidth Fee Mechanisms for Certified Transaction Dissemination"
collection: publications
category: conferences
permalink: /publication/2026-09-30-bandwidth-fee-mechanisms
excerpt: This study develops bandwidth fee mechanisms for pricing threshold certified transaction dissemination before consensus.
date: 2026-09-30
venue: 'WINE 2026 Conference Proceedings'
slidesurl: 
paperurl: '/files/Bandwidth_Fee_Mechanisms.pdf'
bibtexurl: 
citation: 
---
Abstract:

We study bandwidth fee mechanisms (BFMs) for pricing threshold certified transaction dissemination before consensus. BFMs are
analogous to transaction fee mechanisms (TFMs) introduced by Roughgarden (2021), except that they price blockchain communication
rather than computation. Separately pricing this bandwidth is especially relevant when transaction dissemination is separated from
consensus and execution. We model BFMs as a two-sided procurement auction between users who submit transactions and validators who
receive and forward them. Any validator may be assigned as the source of a transaction and forward it to a threshold of attesters.
The model accounts for the source validator's receipt of the user submitted transaction and the subsequent transfers between
validators. It abstracts away unrestricted multi-hop gossip and network topology.

In this work, we focus on settings where transactions must be certified/attested by a threshold of network nodes before consensus,
and we develop the following results.

* We characterize the limits of myopic incentive compatibility for BFMs: No non-trivial transcript-based BFM can prevent profitable
  collusion between two validators, and no non-trivial BFM can simultaneously satisfy incentive compatibility for individual user,
  individual validator, and coalition of one validator and one user.
* In contrast, once we restrict attention to unilateral deviations, we present a greedy-route posted-price mechanism that is
  incentive compatible for every individual user and validator.
* We study how the bandwidth price should evolve across blocks. Assuming validators execute honestly, we propose an EIP-1559-style
  price-update rule and show that its fluid approximation has a unique fixed point, which is locally stable for small enough step
  sizes. In large markets, prices that start near this point stay near it with high probability over any fixed time horizon.

See the full paper [here](/files/Bandwidth_Fee_Mechanisms.pdf). Link to the WINE 2026 proceedings coming soon.
