# WAX Cheat Sheet

## At a Glance
* Consumer friendly onboarding.
* Fast, high-capacity and low-fee, relative to peers.
* DPoS and reasonably decentralized.

## Tokens
* **WAXP** - Protocol token.
* **WAXE** - ERC-20, defi token.
* **WAXG** - ERC-20, governance token.

## History
WAX was founded in 2017, by the creators of [OpSkins](https://en.everybodywiki.com/OPSkins), a successful video game 'skin' marketplace. The CEO, William Quigley, is a well known VC, early investor of Paypal, Ethereum and founder of Tether. Starting as an ERC-20 token, the WAX team realised that ETH was never going to meet the performance requirements of mass market activity. After exploring options, a Delegated Proof of Stake model was chosen on the EOSIO protocol.

## Infrastructure
* **Block Producers** - On WAX BPs are called 'Guilds'. Guilds are voted in by a team of 3 democratically elected community representatives (called 'Inspector Generals'). Guilds are awarded points based on their contribution to the ecosystem and are re-evaluated every 6 weeks. The top 21 Guilds in this system are voted in to validate blocks (round-robin). Up to 32 additional Guilds are availible on standby. 
* **Resource Model** - WAX uses a resource model for on-chain actions. WAXP staked to resources yields rewards, ~4% APY.
  - **CPU** - CPU time is awarded to users based upon the amount of WAXP a user has staked to CPU. Every transaction consumed a daily allocation of CPU, CPU is refunded 24 hours after a transaction is made.
  - **NET** - Similar principle to CPU.
  - **RAM** - Unlike CPU/NET, RAM must be bought and sold. All on-chain elements (accounts, NFTs, etc) consume RAM.

## Stats
Sources: [EOSAuthority](https://eosauthority.com/?network=wax), [Blockivity](https://blocktivity.info/)
* **Wallets** - 12.8m.
* **TPS** - Mainnet peak: 4209. Theoretical limit: 12,000. Daily average: ~300.
* **Txn Volume** - 20-25m daily average.
* **Block Time** - 1s.
* **Fees** - No fees. Transactions consume 'CPU'. Refreshed after 24 hours.
* **Exchanges** - Binance, KuCoin, Bittrex, Upbit, HitBC.

## Material Partnerships
* **Funko** - A global brand with regular NFT collections on WAX. Rare NFTs entitle owners to unique real-world toys. [Source](https://funko.droppp.io/)
* **AMC and Sony** - First 86k consumers to purchase a cinema ticket (US only) were awarded a WAX NFT. [Source](https://www.pcmag.com/news/amc-and-sony-are-giving-away-spider-man-nfts)
* **Mattel** - Similar to Funko, Hotwheels NFTs are on WAX, with unique real-world collectibles. [Source](https://licensinginternational.org/news/mattel-partners-with-wax-to-release-hot-wheels-nft-garage-series-1/)
* **Hasbro** - Power Ranger NFTs. [Source](https://corporate.hasbro.com/en-us/articles/hasbro_makes_nft_debut_with_power_rangers_collection_on_wax)
* **Capcom** - Street Fighter NFTs with crafting mini-game. [Source](https://medium.com/wax-io/street-fighter-v-back-on-wax-77f92f420170)

## Noteworthy Features
* **Largest NFT Drop** - 10 million wallet celebration event saw 10 million NFTs minted. [Source](https://decrypt.co/90781/wax-give-10-million-free-nfts-largest-ever-nft-drop)
* **Cloud Wallet** - The WAX Cloud Wallet is a custodial, non-tech friendly solution (perfect for gamers), designed to reduce onboarding friction. Users can create a blockchain address ('accounts' on EOSIO) with social logins and purchase crypto with standard credit cards from within the wallet. Non-custodial accounts are also available on WAX. [Source](https://wallet.wax.io/)
* **WAX IP** - WAX filed thousands of blockchain technology patents prior to the NFT boom. The concept of linking real-world merchandise to NFTs was invented and patented by WAX, they call this concept 'vIRLs'. These patents are expected to be enforced when it is most effective to do so. [Source](https://twitter.com/wax_io/status/1417242848555057160?s=28andt=B2iTWBCxkrl6yZjr6NSHDA), [Patents](https://patents.justia.com/inventor/jonathan-yantis)
* **Games** - Alien Worlds (TLM token), Farmers World (FWW, FWG, FWF tokens), Blockchain Brawlers (BRWL) and Splinterlands (NFT only) are market leading P2E projects on WAX.
* **NFTs** - The [Atomic Assets](https://github.com/pinknetworkx/atomicassets-contract/wiki) token standard is highly regarded solution for NFT creation. It enables NFT staking, burning, backing, and many other modern NFT features. Media for WAX NFTs can be pinned to decentralised storage layers. Many of the NFT creation tools on WAX automatically pin to IPFS.

## Future Targets
* **Gaming** - WAX is focusing efforts on creating high quality gaming experiences. The first game, Blockchain Brawlers demonstrates a stable and lucrative economy, despite having virtually zero gameplay. WAX is reportedly working on 2 additional game projects.
* **Cross-Chain** - ETH and BSC bridges have been implemented on WAX in various forms. WAX will utilise this more in the future, as a tool to bring over users from 'inferior' chains.
* **Metaverse** - Not yet announced, there's uncertainty if this is a genuine effort or a marketing tool.
* **EVM** - Similar to the metaverse, the development of an EVM has been reported, but there has been no development updates.
* **Scaling** - Scaling solutions are a concern for all blockchains, due to the higher capacity, WAX have more time than others to implement a solution.

## Challenges
* **Token Access** - WAXP is not listed on important exchanges like Coinbase and FTX. This is a priority for users, especially in the US, with limited access to Binance.
* **Marketing** - Industry presence is low, despite the fundamental successes, consumers are relatively unaware of WAX. This is reflected in the current market cap and is a result of not prioritising marketing and PR. This has become a focus recently.
* **Dev Tooling** - No OAuth interface for the cloud wallet and limited gaming SDKs (Unity, but no Unreal).