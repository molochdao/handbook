---
description: Appropriated from DAOhaus documentation. Requires revising.
---

# Features Overview

### Members, Shares and Loot <a href="members-shares-and-loot" id="members-shares-and-loot"></a>

The DAOhaus platform helps us manage stakeholders within our DAO (i.e. **Members**). **Members** are people or organizations that own **Shares** and **Loot** in MolochDAO. **Members** can own both **Shares** and/or **Loot**.

![](https://daohaus.club/assets/images/ua\_memberview-6a1d062eac0e1cd8c997748e28ef4cbc.png)

> When a **Member** owns **Shares**, they have an economic share of the funds in the DAO's **Bank**, as well as voting rights in the DAO's **Proposals**.

> When a **Member** owns only **Loot**, they only have an economic share of the funds in the DAO's **Bank**, but not voting rights in the DAO's **Proposals**.

Non-members can join the DAO by requesting for Shares / Loot via a Membership **Proposal**. **Members** can leave the DAO through a **RageQuit** proposal, thereby withdrawing their pro-rated ownership of the **Bank**'s funds.

### Proposals & Voting <a href="proposals--voting" id="proposals--voting"></a>

Decision making is done via **Proposals**, which will need to be voted on by **Members** (based on their respective Share counts)

![](https://daohaus.club/assets/images/how\_\_proposals-f29ed4c8c4644af334408bb7800c6a51.png)

Common types of **Proposals** are:

* Membership - Tributing capital and Requesting new shares to join the DAO
* Funding - Tributing or Requesting funds from the DAO to work on internal projects and improvements
* Whitelist - Request to add support for a new ERC20 token
* GuildKick - Request to forcibly remove a malicious member through a vote
* Minion - A contract that allows execution of arbitrary calls i.e swapping assets in the DAO bank

The stages for **Proposals** are:

* Submit Proposal
* Sponsor Proposal
* In Queue
* Voting Period
* Grace Period
* Ready for Processing
* Completed

### Bank & Token <a href="bank--token" id="bank--token"></a>

The **Bank** holds all the DAO funds, which include ERC-20 (excluding native tokens such as ETH, xDAI, MATIC on the respective chains) and ERC-721 NFTs.

![](https://daohaus.club/assets/images/bank\_screenshot-e4b311ca97b1e385b05b9fd906169a6c.png)

> Native tokens must be wrapped first before being sent to the Bank. Alternatively, DAOs can set up a Minion that allows the holding of native tokens.

For an ERC-20 token to show up in the Bank's balance, the DAO must whitelist the token via a Whitelist Proposal (Tutorial here)

### Minion & Boosts <a href="minion--boosts" id="minion--boosts"></a>

Beyond the core functions of managing membership, proposals and funds, DAOhaus has **Minions** and **Boosts** that help to add extra functionality to your DAO (you can think of them like apps)

**Boosts**, in general, give you extra functionality to your DAO (e.g. adding a Discord bot to your DAO).

If you need to interact with smart contracts (e.g. swapping tokens, managing LP positions, etc.), **Minion** help you with making arbitrary calls to smart contracts.
