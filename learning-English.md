# 📚 Bitcoin Resources in English

A curated list of tools, links, guides, and communities to help anyone get started with Bitcoin. No shitcoins. Always evolving.

---

## 🟠 1. Where to Start
- Quick guides, beginner videos, 101s
- [Bitcoin White Paper](https://bitcoin.org/bitcoin.pdf)

## 📖 2. Deep Dives

### 2.1 Videos
### 2.2 Articles
### 2.3 Books

- [Mastering Bitcoin: Programming the Open Blockchain (3rd Edition) - by Andreas M. Antonopoulos, David A.](https://github.com/bitcoinbook/bitcoinbook)
- [Mastering the Lightning Network (1st Edition) - Andreas M. Antonopoulos, Olaoluwa Osuntokun, Rene Pickhardt](https://github.com/bitcoinbook/bitcoinbook)
  
### 2.4 Courses

- [Plan ₿ Network - Courses](https://planb.network/en/courses)
  
### 2.5 Podcasts & Audio

## 💬 3. Community

### 3.1 Forums 
### 3.2 Telegram / Discord
### 3.3 Meetups & Events
### 3.4 Git repositories

- [Lightning Network Limitations – by renepickhardt](https://github.com/renepickhardt/Lightning-Network-Limitations)  
  This repository contains Jupyter Notebooks and research papers that investigate the technical limitations of the Bitcoin Lightning Network protocol, particularly regarding its scalability for processing payments. It provides both theoretical insights and practical analysis of bottlenecks and constraints in the network.
- [Plan ₿ Network](https://github.com/PlanB-Network/bitcoin-educational-content)
  Plan ₿ Network supports Bitcoin education worldwide. This repo contains courses, tutorials, resources, and more.
- [LND - Lightning Network Daemon (Golang)](https://github.com/lightningnetwork/lnd)
- [c-lightning - A Lightning Network implementation in C](https://github.com/ElementsProject/lightning)

## 🛠️ 4. Tutorials & Tools

### 4.0 Bitcoin fundamentals

- [How Bitcoin works, how to use it, and how to work with it as a programmer (if you want to)](https://learnmeabitcoin.com/)

### 4.1 Full Node Setup

- [Bitcoin Core - Running a full node](https://bitcoin.org/en/full-node)

  
### 4.2 Lightning Network

- [Lightning Network White Paper](https://lightning.network/lightning-network-paper.pdf)
- [Splicing: resize Lightning channels](https://lightningsplice.com/splicing_explained.html)
- [LN Markets: LN Exchange for bitcoin futures and options](https://lnmarkets.com/en/)
- [PeerSwap - P2P BTC LN Balancing Protocol](https://www.peerswap.dev/)
- [Lightning Terminal (LiT) is a browser-based interface for managing channel liquidity](https://github.com/lightninglabs/lightning-terminal)
- 
  
### 4.3 Custody & Privacy

## 💰 5. Acquiring Bitcoin

### 5.1 P2P / Non-Custodial


- [Spike to Spike](https://spiketospike.com)  
  A P2P platform for private trading of Bitcoin (BTC) and Tether (USDT), with no KYC required.

- [Best Wallet](https://bestwallet.com/es/)  
  A global P2P platform with no KYC, supporting over 60 blockchains and enabling direct user-to-user trading.


### 5.2 Custodial exchanges
### 5.3 No-KYC options

- [KYCNotMe](https://kycnot.me/) - Several services without KYC

### 5.4 Recommended wallets

- [Electrum](https://electrum.org)
    A lightweight, secure, and non-custodial wallet for storing and accumulating BTC. You retain full control of your private keys.

## 🧾 6. Bitcoin for Businesses

## 🛒 7. Where to Spend Bitcoin

## 📚 8. Essential Glossary
This section defines essential terms and concepts in the Bitcoin and Lightning Network ecosystems. It is divided into two subsections: Bitcoin fundamentals (8.1) and Lightning Network technology (8.2). Whether you're a beginner or building deeper expertise, this glossary is your go-to reference.

---

### 8.1 Bitcoin

**Bitcoin (BTC):**  
A decentralized digital currency invented in 2008 by Satoshi Nakamoto. It enables peer-to-peer transactions without intermediaries, secured by cryptography and recorded on a public ledger called the blockchain.

**Satoshi Nakamoto:**  
The pseudonymous creator(s) of Bitcoin. Their identity remains unknown as of today.

**Blockchain:**  
An append-only, cryptographically secured digital ledger composed of blocks. Each block contains a list of transactions and is linked to the previous block using a hash.

**Block:**  
A container for a batch of Bitcoin transactions, including a reference to the previous block and a nonce used in proof of work.

**Genesis Block:**  
The first block in the Bitcoin blockchain was mined by Satoshi Nakamoto in January 2009.

**Mining:**  
The process of creating new blocks involves solving complex computational puzzles, verifying transactions, and securing the network.

**Hashrate:**  
The total computational power used by the Bitcoin network to mine and process transactions.

**Nonce:**  
A number used once in mining, adjusted by miners to find a hash below a certain target difficulty.

**Difficulty Adjustment:**  
Occurs approximately every 2,016 blocks (~2 weeks) to ensure blocks are mined roughly every 10 minutes. It adjusts mining difficulty according to network hashrate.

**Halving:**  
An event every 210,000 blocks (~4 years) that cuts the block reward in half, slowing the rate of Bitcoin issuance.

**Total Supply:**  
Capped at 21 million bitcoins, which ensures scarcity and disinflation over time.

**Private Key:**  
A secret 256-bit number used to sign transactions. Whoever holds the private key controls the associated bitcoins.

**Public Key:**  
Generated from the private key, it is used to derive a Bitcoin address and validate digital signatures.

**Bitcoin Address:**  
A hashed version of the public key used to receive payments. Formats include Legacy (P2PKH), Script (P2SH), and SegWit (Bech32).

**Wallet:**  
Software or hardware that stores private keys. Types include mobile, desktop, hardware, paper, and web wallets.

**Seed Phrase (Mnemonic Phrase):**  
A human-readable backup of a wallet, typically 12 or 24 words. Used to recover private keys.

**Transaction (TX):**  
A digital message signed with a private key that instructs the Bitcoin network to transfer funds.

**TXID (Transaction ID):**  
A unique identifier for a Bitcoin transaction, usually the hash of the transaction data.

**Fee (Mining Fee):**  
An amount paid to miners to prioritize a transaction. Fees are based on size in bytes, not value transferred.

**SegWit (Segregated Witness):**  
An upgrade that separates signature data from transaction data, reducing transaction size and improving scalability.

**Taproot:**  
A major upgrade improving privacy, efficiency, and smart contract functionality by enabling Schnorr signatures and MAST (Merkelized Abstract Syntax Trees).

**Bech32:**  
A SegWit-compatible address format starting with “bc1” that improves error-detection and efficiency.

**Multisignature (Multisig):**  
A setup requiring multiple private keys to authorize a Bitcoin transaction (e.g., 2-of-3 multisig).

**Time Lock / Timelock:**  
A script that restricts when a transaction can be spent. Used in smart contracts and the Lightning Network.

**Orphan Block:**  
A valid block that is not included in the main chain due to another block being accepted at the same height.

**Dust:**  
An amount of Bitcoin too small to spend because the fee would exceed the value transferred.

**Coinbase Transaction:**  
The first transaction in a block, created by the miner, which includes the block reward.

**Change Address:**  
An address used to return leftover Bitcoin back to the sender after a transaction, similar to change in a cash transaction.

**RBF (Replace-by-Fee):**  
Allows a transaction to be rebroadcast with a higher fee to speed up confirmation.

**CPFP (Child Pays for Parent):**  
A fee-bumping method where a new transaction (child) incentivizes miners to confirm a low-fee unconfirmed parent transaction.

**Full Node:**  
A node that fully validates all Bitcoin transactions and blocks. Helps enforce network consensus rules.

**Pruned Node:**  
A full node that discards old block data after validation to save space.

**SPV (Simplified Payment Verification):**  
A lightweight method of verifying transactions without downloading the entire blockchain, used by mobile wallets.

**Cold Storage:**  
Keeping private keys offline to protect against hacking, typically using hardware wallets or paper wallets.

---

### 8.2 Lightning Network

**Lightning Network (LN):**  
A layer-2 scaling solution built on top of Bitcoin that enables fast, low-cost, off-chain transactions through bidirectional payment channels.

**Payment Channel:**  
A temporary, off-chain agreement between two parties that allows for multiple transactions. Only the opening and closing transactions are recorded on-chain.

**Commitment Transaction:**  
A transaction representing the current state of a Lightning channel. Each update creates a new commitment transaction signed by both parties.

**Revocation Key:**  
A mechanism that allows a party to invalidate a prior channel state, used to punish fraud attempts.

**HTLC (Hashed Timelock Contract):**  
Used for routing payments across the Lightning Network securely by combining hashlocks and timelocks.

**Routing Node:**  
A Lightning node that relays payments between other nodes for a small fee.

**Hop:**  
Each intermediary node through which a Lightning payment passes before reaching the recipient.

**Channel Reserve:**  
The minimum amount of satoshis a user must maintain in a channel, preventing it from being closed in an uncooperative way.

**Dust Limit:**  
The minimum amount of satoshis that can be included in a channel update to avoid creating uneconomical outputs.

**Invoice:**  
A BOLT11-encoded string that specifies an amount, expiration time, routing hints, and payment hash.

**Preimage:**  
A secret value used to unlock an HTLC payment. Revealing the preimage proves payment completion.

**Onion Routing:**  
A privacy technique used in Lightning to obscure the full path of a payment by encrypting each hop’s instructions.

**Sphinx Protocol:**  
The cryptographic protocol enabling onion routing in Lightning.

**Anchor Outputs:**  
A mechanism allowing channel participants to attach transaction fees later, making fee estimation more flexible.

**Taproot Channels:**  
Future Lightning channels using Taproot’s improved privacy and efficiency features.

**Dual-Funded Channels:**  
Lightning channels where both participants contribute funds during the opening phase, enhancing liquidity on both sides.

**Splicing:**  
A proposed feature allowing users to add or remove funds from a channel without closing it.

**Watchtower:**  
A service that monitors the blockchain on behalf of offline Lightning nodes to detect and penalize fraud attempts.

**Static Channel Backup (SCB):**  
A file that allows recovery of Lightning funds if a node or wallet is lost. It stores information about channel partners and balances.

**Fee Policy:**  
A routing node’s strategy for charging base and proportional fees for relaying payments.

**Base Fee:**  
A fixed satoshi fee charged per payment regardless of amount.

**Fee Rate (Proportional Fee):**  
A percentage fee charged based on the amount forwarded (e.g., 0.01%).

**Liquidity Management:**  
The practice of balancing inbound and outbound capacity in channels to maintain routing capability.

**Loop (Lightning Loop):**  
A service that allows non-custodial swaps between Lightning and on-chain Bitcoin to manage liquidity.

**Amboss / 1ML / Terminal Web:**  
Popular online tools for visualizing Lightning Network topology and node statistics.

**LSP (Lightning Service Provider):**  
A service offering liquidity, channel management, or infrastructure support to users or merchants on the Lightning Network.

**BOLT (Basis of Lightning Technology):**  
A standardized set of specifications for Lightning implementations to ensure interoperability.

**Zero-Conf Channels:**  
Channels used immediately after funding without waiting for on-chain confirmations—riskier but faster for some use cases.

**Wumbo Channel:**  
A channel larger than the default 0.167 BTC limit, used by advanced users or large-scale services.

---

## 👶 9. Bitcoin for Kids & Families

## 🙋 10. How to Contribute to This List
