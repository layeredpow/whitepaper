Layered PoW: A Scaling Solution for Proof of Work Blockchains DRAFT
==============================================

author

:   Christopher Mercer

email

:   <whitepaper@layeredpow.org>

site

:   <https://layeredpow.org>

**Abstract.** A layered scaling solution for proof-of-work blockchains that maintains the security properties and social composition of the layer 1 network.

Introduction
------------

*describe the current landscape in PoW and clear need to scale L1 PoW*
![](assets/img/section.png)

Goals
------------

*Construct a modular framework to scale the apex chain on a particular PoW mining algorithm. Enable scalability with the native L1 for pure networks. Or scalability with a newly issues L2 network asset*
![](assets/img/section.png)

Potential Research Inspiration
----------------

*Projects that may have tech that could be implemented into this system. Most of blockchain projects have centralized points of failure built into them.*

Bitcoin Ecosystem
+ Bitcoin
+ Early Bitcoin clones
+ Layer 2 Scaling Attempts on Bitcoin (Lightning, Drivechains, BitVM, others?)
+ Delayed PoW and other chains that inherit their security from Bitcoin (Komodo, Syscoin, others?)
+ Rollups (optimistic vs fraud proofs) using arbitrary data allocations in L1 Bitcoin

Ethereum Ecosystem
+ Ethereum Virtual Machine, the original proof of work network. Now labeled Ethereum Classic.
+ Early EVM clones
+ Sidechains like Polygon, Expanse
+ Rollups (optimistic vs fraud proofs) like Arbitrum, Optimism. But not centralized vaporware.
+ Decentralized Sequencers if constrcuting rollups
+ Dapps scaling like dydx. Centralized or nah?

Other Ecosystems:
+ early scaling attempts like Omni, Counterparty, etc.
+ look at other network models like Bitshares, Cardano, Chia, BURST, Filecoin, Cosmos, Polkadot, Stellar, Ripple to see if there is any value.

Derivative networks:
+ Delayed PoW via Komodo
+ Syscoin's dependency on Bitcoin security
+ Lightning Network state channels. Millisats unit of account.

![](assets/img/section.png)

Proof-of-Work
-------------

*Explain PoW, maybe just pull copy from Bitcoin WP*
![](assets/img/section.png)

Layered Blockchains Concept
-------------

*Describe the concept of layered blockchains for scaling*
![](assets/img/section.png)

Applicable Networks
------------

*given security is derived from the layer 1 network. should be a majority chain on an algorithm. examples of blockchains worth building layers on top of include: Bitcoin on SHA256, Ethereum Classic on Ethash, Litecoin/Dogecoin on Scrypt, Monero on RandomX. Others exist but are not large enough to mention at this moment.*
![](assets/img/section.png)

Incentive
---------

*Why would the existing mining ecosystem of a chain want to secure an L2. Additional profitability from L2 rewards, like dual mining. Solves trailing emission dilemma with Bitcoin if L2s contribute to the security budget. L2 network difficulty adds to L1 difficuty, both networks benefit.*
![](assets/img/section.png)

L1 Settlment
---------------------

*Settlement for networks with native currency. For networks with L2 issued currency. Networks with fractionalized L1 currency like Lightning.*
![](assets/img/section.png)

Simplified Payment Verification
-------------------------------

Placeholder
![](assets/img/section.png)

Combining and Splitting Value
-----------------------------

Placeholder
![](assets/img/section.png)

Privacy
-------

Placeholder
![](assets/img/section.png)

Calculations
------------

Placeholder
![](assets/img/section.png)

Conclusion
----------

Placeholder
![](assets/img/section.png)

References
----------

[^1]: Author, \"title,\" <http://whitepaper.org/link>, YEAR.
