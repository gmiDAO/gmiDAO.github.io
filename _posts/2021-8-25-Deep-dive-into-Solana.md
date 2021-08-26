---
layout: post
title: Deep Dive into Solana w. Chris McCann + links to other SOL reads
---

Chris McCann is general partner at Race Capital, entrepreneur, and community builder.

Prev to Race, founded and led the network and community ecosystem at Greylock Partners (Coinbase, Blockstream, and Xapo...). After leaving Greylock, did VC (2017 - Binance, 2018 - Solana [in it for the team], 2019 - FTX...).

Now very supportive of infrastructure and [SOL's ecosystem startups](https://solana.com/ecosystem/#).

### How do we categorize Solana?

Layer1 protocol - the thing people build apps on top of, where all transactions are processed.

Different layer1s have different considerations. SOL is developer-centric and optimized for high speed and low costs.

SOL's token is SPL token.

One is a SOL user via a SOL wallet. This wallet can be used to interact with SOL's apps (e.g. [buy degens](https://www.degenape.academy/)). SOL's userbase comprises devs (exchanges included here), traders, and app users.

### What drives your attention in the crypto industry?

1. Its complexity. Back in the day (t<2017) crypto was a very simple industry. Now people talk of the crypto industry as a whole but it entails many layers (Infrastructure (ETH), Consumer (NFTs), Financial (DeFi), ...). SOL is only 1 ecosystem among many. VCs look at SOL's projects very similarly to normal-world ventures.
2. Infrastructure. Infra is my thing - consumer layer not his sweet spot.

    > *"Do things that you are interested in and use the stuff yourself to learn!"*

3. Communities. There are large communities around this. These are built from the bottom up, not up-down. Very interesting.

### I want to get involved in Solana and I have $1k - what do I do?

Create a wallet ([download Phantom](https://phantom.app/) and create your wallet [*]), buy SOL (from [FTX markets](https://ftx.com/trade/SOL/USD) or any others) and send it to your wallet (your public key) - now ready to use SOL apps.

Go to [Saber](https://saber.so/) and use one of its products (e.g. allocate usdt and usdc in the usdt/usdc pool and start earning yield)

> *"Going through the whole process will teach more than reading, viewing, listening... Also, you will learn the pros and cons of these products"*

[*] Make sure to store your private key securely

### What differentiates Solana and the other protocols?

Its scalable composability without need for [layer 2s](https://coinmarketcap.com/alexandria/article/what-are-cryptocurrency-layer-2-scaling-solutions)/[sharding](https://www.investopedia.com/terms/s/sharding.asp).

Speed and cost. If the previous process was done in ETH, one would need >$1K (ETH's gas fees can be huge ~$1-65) and hours (ETH's transactions take ~10-30mins to confirm) to be safe. In SOL, one can do it with $10 (fees under cents) and 30 minutes (sometimes, clicking bottoms takes more than confirming the transaction).

SOL offers good UX without sacrificing much on decentralization.

### Solana winning then?

Crypto is so early that no one is competing - the industry not prepared for mass adoption yet. Once things get into scale... yes, there will be competing communities.

### Why do anonymous apes follow me?

2 weeks ago took place the Degen NFT sale. People want to remain anonymous and owning an image that represents them seems to have reached PMF - first tiny move to the metaverse?

### What about Solana's centralization topic?

True that SOL has a smaller set of validators in comparison with PoW Solutions. But some PoW solutions, not so decentralized - e.g. BTC's miners are huge industrial conglomerates. SOL's high throughput makes it hard to bootstrap a whole node, but SOL is not that bad - currently [999 validators](https://solanabeach.io/validators) and [Stake Pool Program](https://spl.solana.com/stake-pool) (SOL's Dev Team continuously working on improving SOL).

There is a strong ethos that things must be architectured so everyone with a raspberry pi can participate. SOL is fast cuz its tech stack [1] (optimized for high-end GPUs) and its consensus mechanism ([PoH](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)) - SOL is more practical, less religious.

---
Thank you [@Mat_Sherman](https://twitter.com/Mat_Sherman?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1430210742670696449%7Ctwgr%5E%7Ctwcon%5Es1_&ref_url=https%3A%2F%2Fpublish.twitter.com%2F%3Fquery%3Dhttps3A2F2Ftwitter.com2Fmiche_yu2Fstatus2F1430210742670696449widget%3DTweet) for hosting this interview at [@Clubhouse](https://twitter.com/Clubhouse)

---

[1] *"There are 8 key innovations that make the Solana network possible*" by Anatoly Yakovenko, Founder and CEO at Solana.

- **[Proof of History (POH)](https://medium.com/solana-labs/proof-of-history-a-clock-for-blockchain-cf47a61a9274)** — a clock before consensus;
- **[Tower BFT](https://medium.com/solana-labs/tower-bft-solanas-high-performance-implementation-of-pbft-464725911e79)** — a PoH-optimized version of PBFT;
- **[Turbine](https://medium.com/solana-labs/turbine-solanas-block-propagation-protocol-solves-the-scalability-trilemma-2ddba46a51db)** — a block propagation protocol;
- **[Gulf Stream](https://medium.com/solana-labs/gulf-stream-solanas-mempool-less-transaction-forwarding-protocol-d342e72186ad)** — Mempool-less transaction forwarding protocol;
- **[Sealevel](https://medium.com/solana-labs/sealevel-parallel-processing-thousands-of-smart-contracts-d814b378192)** — Parallel smart contracts run-time;
- **[Pipelining](https://solana.com/pipelining-in-solana-the-transaction-processing-unit/)** — a Transaction Processing Unit for validation optimization
- **[Cloudbreak](https://medium.com/solana-labs/cloudbreak-solanas-horizontally-scaled-state-architecture-9a86679dcbb1)** — Horizontally-Scaled Accounts Database; and
- **[Replicators](https://medium.com/solana-labs/replicators-solanas-solution-to-petabytes-of-blockchain-data-storage-ef79db053fa1)** — Distributed ledger store

→ **More reads on SOL:**

[*"Why we are bullish on Solana*"](https://github.com/sinoglobalcap/investment-theses/blob/main/english/solana.md) by Sino Global Capital

> *Solana fills a major performance gap in the world of blockchains while remaining decentralized and composable. A bet on Solana is a bet that one day we will need fully decentralized systems that can support thousands of high-value complex transactions per second and that the chain that can support that scalability and finality today will accrue significant value.*

[*"Technical Scalability Creates Social Scalability*"](https://multicoin.capital/2021/05/25/technical-scalability-creates-social-scalability/) by Kyle Samani, MP at Multicoin Capital

> *Because it natively executes transactions in parallel on GPUs, it can take advantage of the massive gains in parallelism that GPUs provide.*
> Solana literally scales at the limits of physics - S*olana is the only blockchain that natively supports intra-shard parallelism via its SeaLevel runtime. SeaLevel executes transactions natively on GPUs. When Nvidia releases new GPUs in 12-24 months with 8,000 cores, the Solana network’s computational bandwidth will roughly double.*

[*"Composability is Innnovation*"](https://future.a16z.com/how-composability-unlocks-crypto-and-everything-else/) by Linda Xie, co-founder of Scalar Capital

> *Developers can bootstrap their own projects and communities without having to build everything from scratch [...]*
> *Non-crypto businesses can increase efficiency and have more functionality by plugging into open ecosystems [...]*
> *Developers can learn and apply concepts from a broad variety of industries [...]*
