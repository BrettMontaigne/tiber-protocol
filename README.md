# tiber-protocol
Tiber, a liquid staking protocol on Algorand - 2022 International School on Algorand Smart Contracts

# why liquid staking?

In a Proof-of-Stake framework, a user stakes funds to a protocol in exchange for rewards. Traditionally staked funds are locked and inaccessible to the staker for a certain period. This introduces risk to the party staking funds.

Liquid staking (or "soft" staking) is a protocol that enables access to staked funds mediated by a staking token. It lowers risk for users staking funds to a protocol by retaining access to their funds, mediated by this staked token. 

# current state of the art

Some high profile examples of liquid staking protocols on different blockchains include Lido Finance on Ethereum and Blockdaemon's implementation on ETH2. Lido finance mediates their staking protocol via a cohort of proxied contracts (Solidity), with a primary contract that negotiates the staked liquidity token pool. Lido is behind a transparent upgradeable contract. Lido is also organized as a DAO with supplementary DAO contracts. 

In many ways liquid staking is technically similar to and an extension of flash minting. In a flash mint, a flashed token is minted, backed and redeemable by an underpinned token. This is the engine that powers liquid staking contracts. 

# advantages & applications

Liquid staking increases participation in the base protocol by reducing risk for capital and development. Our team identified that liquid staking was missing from the modern DeFi stack for Algorand, currently there is not a high-profile liquid staking protocol on Algorand.

Yield farming is a significant application of liquid staking, reducing risk and complexity for yeild farming activities between a diversity of funds. A robust liquid staking protocol on Algorand will help open the door to more yield farming activity on Algorand's ecosystem. 

# challenges

Given our research there is no congruent liquid staking protocol on Algorand. Our team will reverse engineer current state of the art liquid staking protocols in the Ethereum ecosystem, and develop a set of core TEAL contracts via PyTEAL bindings. We will aim to engineer this in a way that encourages decentralized governance, transparent upgradeability, and best practices in smart contract security. 
