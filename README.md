<div align="center">

# Decibells

Open protocol for claims anyone can check and challenge.

TypeScript · libp2p · IPFS · PostgreSQL

<img src="https://img.shields.io/badge/In%20development-F59E0B?style=flat-square" alt="In development">


Decibells is an open protocol for claims you can check. Anyone can publish a claim with its evidence, like
"this file existed on this date", "this dataset gives this result" or "this release was built from this
source", and anyone can challenge it. A claim stands until someone shows it is wrong. Nobody is paid and
nothing is staked, so there is nothing to win by gaming it.

| | |
|:---|:---|
| **Claims** | A statement and its evidence, signed, stored on IPFS and given a permanent link |
| **Checks** | Signatures, file fingerprints and timestamps are verified automatically, and results are recomputed |
| **Challenges** | Anyone can dispute a claim with counter-evidence, and the dispute stays attached to it |
| **Reviews** | When a machine can't settle a dispute, reviewers rate it, and a verdict shows only when people who usually disagree agree, as with Community Notes |
| **Reputation** | Reviewers earn standing when their verdicts hold up; it can't be bought or transferred |

Nodes share claims over libp2p, so no single server holds them and any node can re-check any proof.
Timestamps are anchored with OpenTimestamps. It suits evidence that can be published: documents, datasets
and software releases.

</div>
