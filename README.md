DIRTYDEEDS Core integration/staging repository
=====================================

[![Build Status](https://travis-ci.org/DIRTYDEEDS-Project/DIRTYDEEDS.svg?branch=master)](https://travis-ci.org/DIRTYDEEDS-Project/DIRTYDEEDS) [![GitHub version](https://badge.fury.io/gh/DIRTYDEEDS-Project%2FDIRTYDEEDS.svg)](https://badge.fury.io/gh/DIRTYDEEDS-Project%2FDIRTYDEEDS)

DIRTYDEEDS is an open source crypto-currency focused on fast private transactions with low transaction fees & environmental footprint.  It utilizes a custom Proof of Stake protocol for securing its network and uses an innovative variable seesaw reward mechanism that dynamically balances 90% of its block reward size between masternodes and staking nodes and 10% dedicated for budget proposals. The goal of DIRTYDEEDS is to achieve a decentralized sustainable crypto currency with near instant full-time private transactions, fair governance and community intelligence.
- Anonymized transactions using the [_Zerocoin Protocol_](http://www.dirtydeeds.org/zdid).
- Fast transactions featuring guaranteed zero confirmation transactions, we call it _SwiftX_.
- Decentralized blockchain voting utilizing Masternode technology to form a DAO. The blockchain will distribute monthly treasury funds based on successful proposals submitted by the community and voted on by the DAO.

More information at [http://95.179.233.165/](http://95.179.233.165/)   

### Coin Specs
<table>
<tr><td>Algo</td><td>Quark</td></tr>
<tr><td>Target spacing</td><td>9 min.</td></tr>
<tr><td>Timespan</td><td>18 min.</td></tr>
  <tr><td>Trans. conf.</td><td>9</td></tr>
<tr><td>Max Coin Supply (POW Phase)</td><td>810,000 DID</td></tr>
  <tr><td>Rewards (PoW Phase)</td><td>45 DID</td></tr>
  <tr><td>Last POW block</td><td>18000</td></tr>
<tr><td>Max Coin Supply (POS Phase)</td><td>Inf*</td></tr>
  <tr><td>Rewards (POS Phase)</td><td>54 DID</td></tr>
    <tr><td>RPC/P2P ports</td><td>5779/5780</td></tr>
     <tr><td>MN amount</td><td>3600 DID</td></tr>
   <tr><td>MN rewards</td><td>63%</td></tr>
       <tr><td>MN conf.</td><td>18 DID</td></tr>

  
</table>




### More nodes for fast sync.

<table>
<th colspan=4>Nodes</th>
<tr><th>#</th><th>IP</th><th>Port</th></tr>
<tr><td>1</td><td>199.247.25.83</td><td>5780</td></tr>
  <tr><td>2</td><td>108.61.99.191</td><td>5780</td></tr>
  <tr><td>2</td><td>95.179.198.12</td><td>5780</td></tr>
  <tr><td>2</td><td>140.82.36.143</td><td>5780</td></tr>
  <tr><td>2</td><td>140.82.32.102</td><td>5780</td></tr>
  <tr><td>2</td><td>217.69.12.31</td><td>5780</td></tr>
</table>

### PoW Rewards Breakdown

<table>
<th>Block Height</th><th>Masternodes</th><th>Miner</th><th>Budget</th>
<tr><td>2-43200</td><td>20% (50 DID)</td><td>80% (200 DID)</td><td>N/A</td></tr>
<tr><td>43201-151200</td><td>20% (50 DID)</td><td>70% (200 DID)</td><td>10% (25 DID)</td></tr>
<tr><td>151201-259200</td><td>45% (22.5 DID)</td><td>45% (22.5 DID)</td><td>10% (5 DID)</td></tr>
</table>

### PoS Rewards Breakdown

<table>
<th>Phase</th><th>Block Height</th><th>Reward</th><th>Masternodes & Stakers</th><th>Budget</th>
<tr><td>Phase 1</td><td>259201-302399</td><td>50 DID</td><td>90% (45 DID)</td><td>10% (5 DID)</td></tr>
<tr><td>Phase 2</td><td>302400-345599</td><td>45 DID</td><td>90% (40.5 DID)</td><td>10% (4.5 DID)</td></tr>
<tr><td>Phase 3</td><td>345600-388799</td><td>40 DID</td><td>90% (36 DID)</td><td>10% (4 DID)</td></tr>
<tr><td>Phase 4</td><td>388800-431999</td><td>35 DID</td><td>90% (31.5 DID)</td><td>10% (3.5 DID)</td></tr>
<tr><td>Phase 5</td><td>432000-475199</td><td>30 DID</td><td>90% (27 DID)</td><td>10% (3 DID)</td></tr>
<tr><td>Phase 6</td><td>475200-518399</td><td>25 DID</td><td>90% (22.5 DID)</td><td>10% (2.5 DID)</td></tr>
<tr><td>Phase 7</td><td>518400-561599</td><td>20 DID</td><td>90% (18 DID)</td><td>10% (2 DID)</td></tr>
<tr><td>Phase 8</td><td>561600-604799</td><td>15 DID</td><td>90% (13.5 DID)</td><td>10% (1.5 DID)</td></tr>
<tr><td>Phase 9</td><td>604800-647999</td><td>10 DID</td><td>90% (9 DID)</td><td>10% (1 DID)</td></tr>
<tr><td>Phase X</td><td>648000-Infinite</td><td>5 DID</td><td>90% (4.5 DID)</td><td>10% (0.5 DID)</td></tr>
</table>
