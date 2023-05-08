<p align="center"><img src="/client/public/img/main.png" width="300"></p>
<h6 align="center">DeFi aggregator that unites the liquidity of decentralized exchanges into one comprehensive interface via ibc.</h6>

- [Presentation File 🔗](https://www.canva.com/design/DAE5AbJGNFU/nVl3f4oPNXXRHHvFJg47qQ/view)
- [Presentation Video 🔗](https://vimeo.com/824908962)
- Deployed Contract
  - IBC Relayer : `ibc/85F860A9556E285E2F5E6CBC39F04E8E7A497488B9E7D11912030EB49D5E2CCB`
  - Injective Testnet InterSwapX aggregator address: `inj19xtqveu7ezny7t83lzmp2u8mezhlejt699clps`
  - Neutron Testnet InterSwapX aggregator address: `neutron1ujq98szygxahnxud8erct5hc4sjhu8v7760rsapagtwutf3p6njqc5zcxf`
  - Osmosis Testnet CrossChain Call contracts : `osmo10qevam8t96htlgz3dr2y8vl573ya3ecenuk0fyeczxlqj8hgpyrs9sc90y`

---

### What it does

- Aggregates liquidity across dexes on all chains to grab the best pools
- Uses IBC to swap tokens crosschain via interchain messaging and Osmosis' crosschain calls
- Set up a relayer in between testnets of Osmosis , Injective and Neutron

### Inspiration

- Users need to continuously bridge to separate chains to grab their assets.
- Current aggregators present in Cosmos only aggregate assets on a single chain
- Due to this the best price the user can get on that chain is limited to the liquidity of that asset on that chain
- Or worse, if that asset is not on chain then user can't exchange that asset

### Tech Stack

- Cosmwasm
- Relayer in Hermes
- Injective, Neutron and Osmosis
- Rust and TS

### Future Scope

- Improving the SDK for better routes and prices
- Introduce multihops for multiple chains using ICS-999

### Team

- [ 👨🏻‍🎓 Arpit Srivastava](https://github.com/fuzious)
- [ 👨🏻‍💻 Aniket Dixit ](https://github.com/dixitaniket)
- [ 🌊 Aman Raj](https://amanraj.dev)
