---
layout: post
type: socratic
title: "Socratic 33"
meetup: https://www.meetup.com/sabitdevs/events/316192558/
---

# Announcements

- Interaction and asking questions are encouraged

# Coldcard Vulnerability
- [User reports their coldcard wallet being drained on reddit](http://www.reddit.com/r/Bitcoin/comments/1vatgl4/full_panic_one_of_my_wallets_was_drained/), [Discussion](https://stacker.news/items/1536238)
- Coldcard communication during and after
    - [Coldcard Mk3 Security Advisory](https://blog.coinkite.com/coldcard-mk3-seed-generation-warning/)
    - [Technical deep dive into the entropy issue](https://blog.coinkite.com/entropy-technical-backgrounder/)
    - [To all Coinkite users and the entire Bitcoin community - NVK](https://x.com/nvk/status/2083216713693151552) 
    - [Adding to the Public Record on Our Ongoing Investigation - Coldcard](https://x.com/COLDCARDwallet/status/2084731768632991801)
    - [Coldcard issues "extremely important correction"](https://x.com/COLDCARDwallet/status/2085541034243600805)

- [Coldcard Mk2, Mk3, Mk4, and Q Firmware Security Vulnerability - block](https://engineering.block.xyz/blog/predictable-rng-fallback-and-32-bit-reseed-in-coldcard-firmware)
- [Tracing the Attacker's Steps Through 1,082 BTC Coldcard Drain - Praveen Perera](https://praveenperera.com/blog/coldcard-mk3-weak-rng-wave1/)
- [Coldcard Entropy Bug: An Investigative History - SimpleStacker](https://stacker.news/items/1540008)
- [Coldcard: the technical autopsy of an entropy failure - Kevin Loaec, Wizardsardine](https://wizardsardine.com/blog/coldcard-vuln-deep-dive/)
- [When random.bytes runs but doesn't work - tuma, btcpp](https://open.substack.com/pub/btcpp/p/when-randombytes-runs-but-doesnt) 
- [Alex Thorn, Galaxy Digital Research](https://x.com/glxyresearch/status/2083623500183421043) [Part 2](https://x.com/glxyresearch/status/2084411904924045370) [Part 3](https://x.com/intangiblecoins/status/2088305623318298903)
- [mapping the ongoing Coldcard attack with a live dashboard - James O'Beirne](https://cktripwire.com/)
- [Coldcard key exposure - orangesurf](https://cktripwire.com/)
- [Coldcard and the limits of "don't trust, verify"](https://bennet.org/blog/thoughts-on-the-coldcard-incident/)
- [There is not 1 single compelling evidence that this was a backdoor - Raw_Avocado](https://stacker.news/items/1540811)
- [Coldcard users allegedly reporting drains since 2022](https://stacker.news/items/1538415)
- [River: Coldcard Exploit Takeaways](https://river.com/content/coldcard-exploit-takeaways)
- [MARA Slipstream "rescues" 9K bitcoin from Coldcard multisigs](https://foundation.mara.com/articles/9k-bitcoin-rescued-out-of-coldcard-multisigs) 
- [Coinkite suspends customer data blanking](https://stacker.news/items/1542564)

# Other Weird Exploits

## Boltz
- [Announcement](https://x.com/Boltzhq/status/2084311537502630319)
- [Blockstream Swaps](https://blog.blockstream.com/announcing-blockstream-swaps/)
- [Swapmarket still operating](http://swapmarket.github.io/)
- [Canary expires](https://stacker.news/items/1540499)
- [Boltz says it was just an oversight](https://x.com/Boltzhq/status/2084980509642281288)

## BTCPay Server
- [Announcement](https://x.com/BtcpayServer/status/2085755643659522240)
- [Response and next steps](https://x.com/BtcpayServer/status/2086875402572562755)
- [How to set up BTCPay Server better after the hack?](https://stacker.news/items/1543355)

## Zeus LSP 
- [Announcement](https://x.com/ZeusLN/status/2084316041673347138) 
- [Post-Mortem](https://zeusln.com/blog/post-mortem-security-update-august-5th-2026/)
 
# BIP 110 Chain Split
- [OCEAN Accused of hashrate hijacking over BIP110](https://xcancel.com/ocean_mining/status/2086623170883399921)
- [Inside OCEAN Mining during the BIP110 chain split - Bob Burnett interview](https://youtu.be/RGexQJfDh5Y)
- [BIP110 debate about new PoW algorithm](https://stacker.news/items/1545902)
- [Luke Dashjr announces sabbatical from OCEAN Mining](https://x.com/i/status/2086919123599036926)
- [Luke Dashjr removed from BIP maintainer role](https://stacker.news/items/1545021) 
- [Lopp post-mortem](https://blog.lopp.net/bip-110-post-mortem/) 
- [Mechanic: It's been 15 years, I'm out](https://stacker.news/items/1549657)
- [Some advice re Luke-less Knots - Siggy](https://stacker.news/items/1545366)

# BIPs
- [BIP54: Great Consensus Cleanup - PR to implement without mainnet activation](https://github.com/bitcoin/bitcoin/pull/35793)
- [BIP95: Testnet 5](https://github.com/bitcoin/bips/blob/master/bip-0095.md)
- [BIP352: Silent Payments functions merged into libsek256k1](https://github.com/bitcoin-core/secp256k1/pull/1765)
- [BIP452: P2P UTXO Set Sharing](https://github.com/bitcoin/bips/pull/2137)
- [BIP453: Terminology of Transaction Components](https://github.com/bitcoin/bips/pull/2195)
- [BIP455-457: SwiftSync Specification](https://github.com/bitcoin/bips/pull/2152)
- [BIP458: Half-Aggregation of BIP 340 Signatures](https://github.com/bitcoin/bips/pull/2205)
- [BIP459: DahLIAS fully aggregated signatures for secp256k1](https://github.com/bitcoin/bips/pull/2210)
- [BIP460: CISA for Taproot Key Path Spends](https://github.com/bitcoin/bips/pull/2210)
- [BIP461: Deterministic ECDSA Signatures](https://github.com/bitcoin/bips/pull/2224)
- [BIP Draft: CHillDKG - Distributed Key Generation for FROST](https://github.com/bitcoin/bips/pull/2227)

# Releases
- [Payjoin Dev Kit 1.0](https://payjoin.org/blog/2026/08/12/announcing-payjoin-1-0/)
- [Ledger Bitcoin v2.5.0 human readable miniscript policies](https://x.com/salvatoshi/status/2086727660353261863)
- [Proof of Work Signet Faucet - ajtowns](https://delvingbitcoin.org/t/proof-of-work-based-signet-faucet/937/8)
- [Breez releases Glow - The Bitcoin App for Everyone](https://breez.technology/glow/)
- [Minerva Mint - Ark-backed Cashu ecash](https://minervamnt.xyz/)
- [Clams v1 - local first accounting for Bitcoin](https://clams.tech/blog/clams-v1-out-of-beta/)

# Research
- [Bitcoin post-quantum R&D tldr](https://brink.dev/blog/2026/08/17/eng-call-conduition-post-quantum/)
- [Dropkick - a minimal commit-reveal rescue protocol - Conduition](https://conduition.io/bitcoin/dropkick/)
- [BIP322 verifier accepts proofs signed by unrelated keys for P2WPKH, P2SH-P2WPKH](https://github.com/rust-bitcoin/bip322/security/advisories/GHSA-5chw-87w3-j9cv)
- [Call to test Bitcoin Core static binaries - Schmidty](https://bitcoinops.org/en/newsletters/2026/08/14/#static-bitcoin-core-binaries-available-for-testing)
- [The DIY Signing Device Revolution is Just Beginning](https://github.com/kdmukai/article-diy-signing-device-summit)
- [How to destroy bitcoin (and what happened to the 107 coins burned in May - bennet](https://bennet.org/blog/how-to-burn-bitcoin/)
- [Anzen: Bitcoin self-custody trilemma - Luke Childs](https://lu.ke/self-custody-trilemma)
- [Omega Splice - Dusty Daemon](https://x.com/dusty_daemon/status/2077065091657195737)

# Tools
- [Bitcoin, Ark, and Nostr decoder](https://github.com/Psycarlo/bitcoin-decoder)

# News
- [Trezor data breach](https://trezor.io/blog/news/recent-customer-data-exposed-in-shipping-provider-incident?ABC)
- [Bitcoin Red Team](https://stacker.news/items/1539074)
- [OpenSats announces priority support for Red Team](https://opensats.org/blog/code-red-supporting-first-responders)
- [Amboss announces affiliate program](https://amboss.tech/blog/amboss-affiliate-program)
- [odudex steps down as krux maintainer](https://github.com/selfcustody/krux/releases/tag/v26.08.0), [JonDoe_le_frog becomes new maintainer](https://x.com/selfcustodykrux/status/2089184624060575749)
- [nix-bitcoin 0.0.139 is final version](https://x.com/nixbitcoinorg/status/2087880779892158679)
- [RY3T Nova: First product built on Mujina - 256 Foundation](https://www.256foundation.org/newsroom/ry3t-nova)
- [Floresta roadmap Q2, Q3 2026](https://www.getfloresta.org/blog/roadmap-Q2-Q3)
- [Wiz seeks support to register top level domain .bitcoin](https://x.com/wiz/status/2085029140453830725)
- [NVK steps down from OpenSats board](https://bxrd.app/note/10e0e0915b1fe8a6df8b959f89c61fee99241874aa2f30ef62669320f89c9cf6)
- [Bitcoin Security Consortium Announced](https://x.com/bitschmidty/status/2080263159152091455)
