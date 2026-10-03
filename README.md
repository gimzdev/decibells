<div align="center">

<h1>Decibells</h1>

<h3>Distributed verification network with token incentives</h3>

[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org)
[![IPFS](https://img.shields.io/badge/IPFS-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white)](https://ipfs.io)
[![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)](https://graphql.org)

<hr>

<h2>About</h2>

<p>Decibells is an attempt at a general-purpose verification network.<br>
When some piece of data matters, you want more than one party to agree on what it says,<br>
and you want that agreement to be provable afterwards.</p>

<p>Validators are paid in tokens for doing the audit work,<br>
and lose stake if they're consistently wrong.<br>
Results are written to IPFS so the record of who verified what is permanent and public.</p>

<hr>

<h2>Flow</h2>

<p><code>Submit → Validate → Consensus → Record → Reward</code></p>

<hr>

<h2>Architecture</h2>

<table align="center">
<tr>
<td align="center" width="33%">

<h3>Network</h3>

libp2p<br>
Byzantine fault tolerance

</td>
<td align="center" width="33%">

<h3>Storage</h3>

IPFS records<br>
Smart contract rules

</td>
<td align="center" width="33%">

<h3>Incentives</h3>

Token rewards<br>
Reputation

</td>
</tr>
</table>

<hr>

<h2>Run a node</h2>

```bash
git clone https://github.com/gimzdev/decibells.git
cd decibells
npm install

npm run node
npm run web
```

<p>The web interface runs alongside the validator<br>
and gives you a view into what the node has been doing.</p>

<hr>

<h2>Use cases</h2>

<p>Supply chain verification, document authenticity,<br>
voting systems, research data integrity.</p>

<hr>

[![Node setup](https://img.shields.io/badge/Node_setup-339933?style=for-the-badge&logo=ethereum&logoColor=white)](https://docs.decibells.network)

</div>
