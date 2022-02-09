# DAOs in 2022 - Solana Riptide Global Hackathon

[MC] [Ryan M. Shea](https://twitter.com/clockwrrk) - [@Solana](https://twitter.com/Solana)

[Sebastian Bor](https://twitter.com/Sebastian_Bor) - Engineering at [@solana](https://twitter.com/solana). Building governance and DAO tooling for on-chain communities 

[Maximilian Schneider](https://twitter.com/m_schneider) - [Mango Markets](https://www.mango.markets/)

**[Realms](https://realms.today/realms) (Governance UI) progress, landscape, roadmap of Solana DAOs?**

Sebastian (3:38) - Lots of progress. Been building the UI of SPL governance version 1 - the UI reflects the features of the contract. General-purpose experience for all DAOS. So far +150 DAOs (Protocol DAOs, NFT collectors DAOs, Charity DAOs, ...) in Realms. Also focused on building something in an asset type and DAO agnostic way - so any DAO can start off.

Sees opportunity in building unique user experiences for different types of DAOs.

About to [release v2 of SPL governance](https://twitter.com/Sebastian_Bor/status/1490780312875458566) which enables to externalize governance power to external contract - only imagination and rust capability is the limit. 

e.g. Mango locker - allows locking [$**MNGO**](https://coinmarketcap.com/currencies/mango-markets/) to gain more governance according to lock period. It also allows the MANGO DAO to give grants and the possibility to claw them back if work is not delivered and other different strategies. It’s a completely reusable plugin of SPL governance.

Expects more plugins like MANGO locker to come. 

NFT based voting or multi-asset governance is now possible. MANGO locker allows using multiple tokens to combine the power of multiple tokens and get creative - e.g. NFT as base + reputation score or non-transferable tokens... Proper way to structure governance is now open for innovation. 

So, for the hackathon - opportunity in the UI side, focusing on different types of DAOs or plugins with different governance structures.

Max (9:41) - Agrees. Having these new possibilities gonna bring lots of conversations (e.g. 100-year MANGO DAO? [4-year vested Curve type model](https://medium.com/nigeriabitcoincommunity/crv-token-is-curve-daos-governance-token-set-to-the-moon-8d88449048ea) with some fine-tuning?). The first step is hard and people will copy what works. Good to have such flexible and configurable tooling. Solana’s most attractive feature is to be able to have a fully functioning working DAO as decentralized as the community is - feels that now the limit is in the community, not tech.

**A bit on Mango - what would you be excited to see on the tooling, support [MANGO DAO](https://dao-beta.mango.markets/dao/MNGO)?**

Max (14:00) - MANGO wants meaningful contributions, to provide liquidity to teams building on top of MANGO. They know a bunch of DAOs that want to move treasury around and can’t. They hope that at the end of the hackathon, more DAO treasury management options are there (e.g. DAOs being able to do things like depositing in programs of protocols, owning governance tokens, owning SOL to run validators...). [Step protocol](https://step.finance/) started on their side and MANGO knew by chance - good moment to get together and build! MANGO would love to be user of other DeFi protocols (focus on stablecoins but generate yield and provide liquidity to other protocols).

Sebastian (18:20) - Sees opportunity in tooling for any kind of DAOs - e.g. for personal DAOs like a family locker DAO,  or creating “social recovery” tooling where if you lose all your keys, you can dedicate a group of people to vote on a recovery proposal periodically to vote on fund access. Tools like these would allow people to manage their wealth differently - enable more people than just crypto natives in a safe way.

Several structures to use this multi-sig. Multi-sig is the simplest DAO (5 people, everyone has one vote and majority of those hands to say yes to move funds). Encourages every team in Solana to start with a multi-sig and grow from there - SPL governance design allows DAOs to grow from a council and once you build the community, give governance power to the community still keeping the council as a safety net and if the community engages the votes goes smoothly, the last layer is to remove the council. The lifecycle of a DAO is very important because DAO is a spectrum, is not one thing. The simplest one is a multi-sig and the other side is decentralized community-owned. Hybrid in the middle of the spectrum. DAO tooling, SPL governance and Realms are designed to allow you to join at any point (but encouraged to start at the beginning).

Everything we do is on-chain and that’s a huge difference for Solana. There is a huge similarity between Realms and [Snapshot](https://snapshot.org/#/) where you can do the same voting. Snapshot off-chain - in Solana votes and the program has executable actions, the vote becomes law and executes the program - no one can stop that. V2 also collecting opinions but is still on-chain. You can measure the quality of a DAO. Sees opportunity in building DAO analytics tools - # users, # people participating in governance, balance sheet... DAO analytics are very useful for the future - if you can measure you can manage.

Max (28:15) - would like to see that - off-chain just a few actors talking loud but then when voting, people get involved. Workflow for making binding decisions increases the seriousness of discussions - 

e.g. MANGO had a not so lucky Twitter vote to see which market to list on and the only way to resolve it was voting on-chain. This act brought the discussion to another level, cuz now not selfish anymore but sth for the greater good - more what’s the right decision independent of best outcome for oneself. More responsibility through transparency - cuz it’s visible what you do and how you vote and to some extent, you can’t really make civil attacks (come with a fake identity or bring all your friends talking loud..) cuz one needs to have the tokens to make the decision. They though was to be enough but now that foundation is in place (SPL governance V2 and full control of the vote count) they have the possibility to integrate way more tightly with the governance. Maybe similar to how Curve is working in ETH where locked tokens directly have an impact on your revenue from the platform - clear steering committee where liquidity incentives are directed and people actually have an influence which made the project really popular cuz every single DAO can influence it. It’s very healthy that MANGO started these discussions.

**Dreaming big, where do you like to see us next time next year DAOs Solana?**

Sebastian (34:57) - we would not only allow creating lots of DAOs but also successful DAOs. Not number but quality.

We have to work towards taking care of blue-chip DAOs - e.g. MANGO is a strong gravitational pool that leads the pack and others try to follow. Would like to see a few very successful DAOs that create this gravitational pool that shows what DAOs can make. 

Max (37:30) - DAO tooling is a flagship product of the Solana ecosystem - only a few applications that really make sense on the blockchain but DAO tooling compelling use for Solana. Idea that we can decide sth together and is fully audited and verifiable on-chain and we can encode structures how much power each has instead if going to a government, putting it into books, going with a lawyer, ... Such dramatic increase accessibility, cost, ... it levels the playfield. A general tool that a lot of projects will be using. [Gnosis Safe](https://gnosis-safe.io/) is very concerned rn thinking about l2 and a strategy that works on l1 and l2... In Solana, we just build and let it run which allows us to run faster and not have to worry about complex execution. His prediction for 2023 is that there is really no reason to have your DAO elsewhere than Solana.

Sebastian (40:20) - thinks we have foundations for that and if we can show the way of how can it be done everything will follow.