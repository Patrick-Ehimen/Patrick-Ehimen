<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=70&section=header"/>
<div align="center">
<a href="https://github.com/Patrick-Ehimen">
  <img src="https://readme-typing-svg.demolab.com/?lines=Patrick+Ehimen+%C2%B7+Software+Engineer;Rust+%C2%B7+Solidity+%C2%B7+TypeScript+%C2%B7+Go;Cross-Chain+%C2%B7+DeFi+%C2%B7+Indexers+%C2%B7+MCP;Smart+Contracts+%C2%B7+Off-Chain+Infra+%C2%B7+Frontend+%C2%B7&font=Fira+Code&center=true&width=600&height=45&color=3B82F6&vCenter=true&size=18&pause=1200" alt="typing" 
</a>
</div>
    
---
    
### About

Blockchain engineer building across — **Typescript** Frontend & Backend, **Rust** systems, **Solidity** contracts, **Solana** programs, and the cross-chain infra that ties them together. I've shipped Uniswap V4 hooks with P2P agent coordination, cross-chain event indexers covering LayerZero, Wormhole, CCIP, and Axelar, and MCP servers that give AI assistants live access to on-chain data. Most of that work lives somewhere between protocol engineering and dAPPS development.

Shipped code across DeFi markets, AMMs, lending protocols, cross-chain bridges, and NFT ecosystems on both EVM and non-EVM chains.
Currently building **[Seraph-Labz](https://github.com/Seraph-Labz)** — a protocol-agnostic cross-chain explorer — and actively contributing to open infrastructure through the PLDG programme.

> Open to protocol engineering, cross-chain infrastructure, Rust systems, and smart-contract and frontend/backend roles. DeFi-focused — AMMs, bridges, indexers, relayers, MCP tooling. [Contact me →](mailto:0xosepatrick@gmail.com)

</div>

---

### Projects I'm working on

<!-- START:featured -->
| Project | Stack | What it does |
| :--- | :--- | :--- |
| **[meridian-rs](https://github.com/Patrick-Ehimen/meridian-rs)** | `Rust` `ratatui` `gRPC` | Multi-exchange orderbook aggregator — CEX + DEX feeds (Binance, Coinbase, Kraken, Uniswap V3, Jupiter), consolidated depth, VWAP, OFI, arbitrage detection, and a live five-panel terminal UI. gRPC + REST + WebSocket servers.  |
| **[chainwright](https://github.com/Patrick-Ehimen/chainwright)** | `TypeScript` `MCP` |  MCPDeFi Protocol MCP server with 40+ tools across 8 modules: token prices, swap quotes, lending health factors, bridge routes, wallet portfolios, protocol TVL, token safety scanning, and transaction simulation. Works with Claude Desktop and any MCP-compatible agent. |
| **[seraph](https://github.com/Seraph-Labz)** | `Typescript` `Rust` | Protocol-agnostic cross-chain explorer — indexes bridge events (LayerZero V2, Wormhole, CCIP, Axelar) across EVM, Solana, and Cosmos. TimescaleDB + Upstash Redis backend, Fastify REST API, Next.js frontend. |

<!-- END:featured -->

---
### Open-source contributions

<p>
  <img src="https://img.shields.io/badge/OpenZeppelin-Contracts_Wizard-4E5EE4?style=for-the-badge&logo=ethereum&logoColor=white" />
  <img src="https://img.shields.io/badge/ChainSafe-Forest_(Filecoin)-1A1A2E?style=for-the-badge&logo=rust&logoColor=white" />
  <img src="https://img.shields.io/badge/Sablier_Labs-Token_Streaming-7B3FE4?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Nethermind-Stellar_Payments-E94560?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Raycast-rust--docs-FF6363?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/DefiLlama-Adapters-00B4D8?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/lighthouse--web3-Package-F5A623?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Akave_AI-SDK_%2F_PLDG-6C47FF?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Storacha-Network_/_Piri-0052FF?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Protocol_Labs-IPFS_/_libp2p-65C2CB?style=for-the-badge&logo=ipfs&logoColor=white" />
</p>

<sub><i>🟣 merged &nbsp;·&nbsp; 🟢 open &nbsp;·&nbsp; 🔴 closed &nbsp;·&nbsp; external repos only</i></sub>

---

<details>
<summary><b>&nbsp;🔒&nbsp; OpenZeppelin / contracts-wizard</b> &nbsp;·&nbsp; Smart contract code generator &nbsp;·&nbsp; <sub>1 PR · 🟣 1 &nbsp;·&nbsp; <a href="https://github.com/OpenZeppelin/contracts-wizard/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🟣 [`#456`](https://github.com/OpenZeppelin/contracts-wizard/pull/456) — Add collapse optional sections by default — optional contract sections (Votes, Access Control, Upgradeability across ERC20 and other types in all languages) now load collapsed; checkbox expands them automatically while still allowing manual expansion to preview child options without activating. Fixes [#449](https://github.com/OpenZeppelin/contracts-wizard/issues/449).

</details>

---

<details>
<summary><b>&nbsp;🦁&nbsp; ChainSafe / forest</b> &nbsp;·&nbsp; Filecoin Rust client &nbsp;·&nbsp; <sub>1 PR · 🟣 1 &nbsp;·&nbsp; <a href="https://github.com/ChainSafe/forest/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🟣 [`#7070`](https://github.com/ChainSafe/forest/pull/7070) — feat: add `DESCRIPTION` to all missing RPC methods — brought OpenRPC description coverage from **133/229 (58%) to 229/229 (100%)** across auth, beacon, chain, network, state, sync, wallet, multisig, market, F3, and Ethereum-compatible method groups

</details>

---

<details>
<summary><b>&nbsp;🌊&nbsp; sablier-labs / indexers + sdk</b> &nbsp;·&nbsp; Token streaming protocol &nbsp;·&nbsp; <sub>5 PRs · 🟣 3 · 🔴 2 &nbsp;·&nbsp; <a href="https://github.com/sablier-labs/indexers/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

**indexers**

- 🟣 [`#276`](https://github.com/sablier-labs/indexers/pull/276) — feat(airdrops): add indexing support for VCA (Variable Claim Amount) campaigns — new schema fields, `createVCA` + `updateForgoneAmount` store functions, `VariableClaimAmount` campaign category enum
- 🟣 [`#275`](https://github.com/sablier-labs/indexers/pull/275) — refactor: convert `Store` namespace exports to object exports — fixes linting blind spot where async `Store` method calls without `await` were undetected by Biome's `noFloatingPromises`
- 🟣 [`#274`](https://github.com/sablier-labs/indexers/pull/274) — Split monolithic 349-line `justfile` into modular domain files (`envio.just`, `graph.just`, `gql.just`, `helpers.just`) — zero breaking changes, all 60+ recipes preserved
- 🔴 [`#294`](https://github.com/sablier-labs/indexers/pull/294) — refactor(envio): replace hardcoded ABI paths with `${ENVIO_ABI_PATH}` env variable; fix RPC config generation to always include Alchemy fallback regardless of codegen-time env

**sdk**

- 🔴 [`#161`](https://github.com/sablier-labs/sdk/pull/161) — test(cron): add bytecode validation for all contracts — `eth_getCode` on every contract address across all releases, pre-fetched in `beforeAll` with deduplication and concurrency cap of 10, exponential backoff matching existing cron patterns

</details>

---

<details>
<summary><b>&nbsp;🔮&nbsp; NethermindEth / stellar-private-payments</b> &nbsp;·&nbsp; Nethermind · Stellar private payment protocol &nbsp;·&nbsp; <sub>3 PRs · 🟣 2 · 🔴 1 &nbsp;·&nbsp; <a href="https://github.com/NethermindEth/stellar-private-payments/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🟣 [`#295`](https://github.com/NethermindEth/stellar-private-payments/pull/295) — feat: add remove non-membership leaf functionality to admin UI — `removeNonMembershipLeaf()` calling `client.delete_leaf({ key })` on the non-membership contract, wallet guard, contract ID validation, status/log/toast feedback
- 🟣 [`#214`](https://github.com/NethermindEth/stellar-private-payments/pull/214) — feat: add push notifications to remind users after 5 days of inactivity — service worker (`sw.js`), `periodicsync` event, Cache API last-visit tracking, onboarding wizard integration
- 🟣 [`#202`](https://github.com/NethermindEth/stellar-private-payments/pull/202) — Fix rustdoc warnings — wrap generic types in backticks, escape bracket notation, convert bare URLs; `cargo doc --no-deps --workspace --release` produces zero warnings

</details>

---

<details>
<summary><b>&nbsp;⚡&nbsp; raycast / extensions</b> &nbsp;·&nbsp; Raycast extension store &nbsp;·&nbsp; <sub>2 PRs · 🟣 1 · 🔴 1 &nbsp;·&nbsp; <a href="https://github.com/raycast/extensions/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🟣 [`#23891`](https://github.com/raycast/extensions/pull/23891) — **Add rust-docs extension** — full Raycast extension for searching the Rust Standard Library (`std`, `core`, `alloc`) directly from the launcher: smart ranking, color-coded type icons, inline formatted docs, cached results, zero-config. Shipped to the [Raycast extension store](https://www.raycast.com/Patrick-Ehimen/rust-docs).
- 🔴 [`#24537`](https://github.com/raycast/extensions/pull/24537) — Update rust-docs extension

</details>

---

<details>
<summary><b>&nbsp;📊&nbsp; DefiLlama / DefiLlama-Adapters</b> &nbsp;·&nbsp; DeFi TVL aggregator &nbsp;·&nbsp; <sub>1 PR · 🔴 1 &nbsp;·&nbsp; <a href="https://github.com/DefiLlama/DefiLlama-Adapters/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🔴 [`#17537`](https://github.com/DefiLlama/DefiLlama-Adapters/pull/17537) — fix: update BNPL Pay adapter to new protocol contracts — old factory `0x7edB0c8b428b97eA1Ca44ea9FCdA0835FBD88029` had been dead since Jan 2023, causing flatline TVL metrics; updated to new proxy `0xa800488...`, restored staking tracking, temporarily disabled borrowed TVL pending v2 interface docs. Closes [#16960](https://github.com/DefiLlama/DefiLlama-Adapters/issues/16960).

</details>

---

<details>
<summary><b>&nbsp;🟠&nbsp; lighthouse-web3 / lighthouse-package</b> &nbsp;·&nbsp; Filecoin storage SDK &nbsp;·&nbsp; <sub>1 PR · 🟢 1 &nbsp;·&nbsp; <a href="https://github.com/lighthouse-web3/lighthouse-package/pulls?q=author%3APatrick-Ehimen">all PRs →</a></sub></summary>

<br>

- 🟢 [`#135`](https://github.com/lighthouse-web3/lighthouse-package/pull/135) — feat: add resilience features — retry, rate limiting, and timeouts — `withRetry` using exponential backoff + jitter; token-bucket rate limiter; `resilientFetch` drop-in for all API calls; `resilientUpload` with progress tracking; `apiConfig.ts` presets for different operation types. Closes [#134](https://github.com/lighthouse-web3/lighthouse-package/issues/134). *Review effort 3/5 label.*

</details>

---

<details>
<summary><b>&nbsp;🔷&nbsp; akave-ai</b> &nbsp;·&nbsp; Decentralised storage SDK &amp; PLDG programme &nbsp;·&nbsp; <sub>5 PRs · 🟣 1 · 🟢 2 · 🔴 2 &nbsp;·&nbsp; <a href="https://github.com/search?q=author%3APatrick-Ehimen+org%3Aakave-ai+is%3Apr&type=pullrequests">all PRs →</a></sub></summary>

<br>

**akavesdk-py** — Python SDK

- 🔴 [`#113`](https://github.com/akave-ai/akavesdk-py/pull/113) — Implement per-file key derivation and fix code quality issues — `encryption_key()` called per upload/download instead of shared key; `chunk.CID` → `chunk.cid` casing bug fixed; 4 bare `except` clauses replaced with specific exception types in `dag.py`; type hints + docstrings added; all 80 encryption and DAG tests pass
- 🟢 [`#111`](https://github.com/akave-ai/akavesdk-py/pull/111) — Add HTTP extension module for range downloads — `HTTPExtClient` with `range_download()` via HTTP Range header; handles 200, 206, 416; Content-Range parsing; streaming to file; 53 unit tests at 99% coverage. Closes [#105](https://github.com/akave-ai/akavesdk-py/issues/105).

**akave-pldg** — PLDG programme proposals

- 🟣 [`#5`](https://github.com/akave-ai/akave-pldg/pull/5) — **Project Proposal: CrossChain Archive** — unified cross-chain indexer (Wormhole, LayerZero V2, Axelar, CCIP) across Ethereum, Arbitrum, Optimism, Base, Polygon; normalized schema, end-to-end message lifecycle tracing, immutable archival to Akave O3, REST/GraphQL API
- 🟢 [`#3`](https://github.com/akave-ai/akave-pldg/pull/3) — **Project Proposal: ZKML Workflows** — ezkl artifact storage on Akave O3; structured layout for circuits, keys, proofs, and model artifacts; CLI workflow runner; automated tests for pipeline reproducibility

**akavelink** — JS SDK

- 🟢 [`#48`](https://github.com/akave-ai/akavelink/pull/48) — feat: enhanced integration tests with error scenarios — network failures, invalid inputs, resource constraints, concurrent operations; performance benchmarking (`response time`, throughput, memory); CLI test runner for specific suites. Closes [#46](https://github.com/akave-ai/akavelink/issues/46).

</details>

---

<details>
<summary><b>&nbsp;💎&nbsp; storacha</b> &nbsp;·&nbsp; Decentralised storage network &nbsp;·&nbsp; <sub>9 PRs · 🟢 5 · 🔴 4 &nbsp;·&nbsp; <a href="https://github.com/search?q=author%3APatrick-Ehimen+org%3Astoracha+is%3Apr&type=pullrequests">all PRs →</a></sub></summary>

<br>

**upload-service**

- 🟢 [`#446`](https://github.com/storacha/upload-service/pull/446) — feat: implement modular UI package architecture with subpath exports — `@storacha/ui/react/components/Authenticator` style tree-shakeable imports; TypeScript project references; Tailwind plugin with CSS custom properties; framework-agnostic core utilities; backward-compatible meta-package

**piri** — PDP storage proof service (Go)

- 🔴 [`#231`](https://github.com/storacha/piri/pull/231) — Add contract generation workflow and submodule — `FilOzone/pdp` added as git submodule at `contracts/pdp`; `scripts/generate-contracts.sh` + `Makefile` targets (`generate-contracts`, `verify-contracts`, `contracts-update`); `go:generate` directive; VERSION file tracking commit hash and timestamp
- 🔴 [`#237`](https://github.com/storacha/piri/pull/237) — feat: enhance CI test failure visibility — structured GitHub workflow output with collapsible groups, failure extraction script, `make test-debug` / `make test-verbose` targets

**indexing-service**

- 🔴 [`#245`](https://github.com/storacha/indexing-service/pull/245) — fix: make deployment depend on test success — `run-tests` + `run-checks` jobs calling `go-test.yml` / `go-check.yml` via `uses:`, all staging/production deploy jobs gated on `needs:` to prevent race-condition deploys of broken main

**storacha.network** — Nuxt.js marketing site

- 🟢 [`#191`](https://github.com/storacha/storacha.network/pull/191) — Add comprehensive testing infrastructure — Vitest (unit/integration), Playwright (E2E), Vue Test Utils + Happy DOM; CI workflow; blog API unit tests; E2E tests for homepage, blog, error pages
- 🟢 [`#190`](https://github.com/storacha/storacha.network/pull/190) — feat: replace console logging with structured logging infrastructure — `consola`-backed logger instances (client, API, blog); request tracing with unique IDs; environment-based log levels; `server/middleware/logging.ts`

**ucan-see-my-request**

- 🟢 [`#28`](https://github.com/storacha/ucan-see-my-request/pull/28) — Add Husky pre-commit hook — Husky + lint-staged for automatic lint/format before every commit
- 🟢 [`#27`](https://github.com/storacha/ucan-see-my-request/pull/27) — chore: add GitHub Actions — PR/push validation workflow and automated release pipeline

</details>

---

<details>
<summary><b>&nbsp;🌐&nbsp; IPFS + libp2p</b> &nbsp;·&nbsp; Protocol Labs ecosystem &nbsp;·&nbsp; <sub>4 PRs · 🟢 3 · 🔴 1 &nbsp;·&nbsp; <a href="https://github.com/search?q=author%3APatrick-Ehimen+org%3Aipfs+org%3Alibp2p+is%3Apr&type=pullrequests">all PRs →</a></sub></summary>

<br>

**ipfs/helia-verified-fetch**

- 🔴 [`#314`](https://github.com/ipfs/helia-verified-fetch/pull/314) — fix: attach server timing to abort errors — `AbortError` now carries a `serverTiming` property with all timing data collected before the abort (DNS resolution, IPNS resolution, etc.) to aid debugging of timeout issues. Fixes [#219](https://github.com/ipfs/helia-verified-fetch/issues/219).

**ipfs/ipfs-check**

- 🟢 [`#121`](https://github.com/ipfs/ipfs-check/pull/121) *(draft)* — feat: add badge endpoint for IPFS availability badges — opt-in `/badge` endpoint generating shields.io-style SVG badges (green/yellow/red/gray by provider count); non-blocking background checks with immediate "checking..." response; in-memory cache with configurable TTL; `--enable-badges` flag + `IPFS_CHECK_ENABLE_BADGES` env var; 32 unit tests. Closes [#118](https://github.com/ipfs/ipfs-check/issues/118). *`status/blocked` pending upstream decision.*

**ipfs/js-kubo-rpc-client**

- 🟢 [`#360`](https://github.com/ipfs/js-kubo-rpc-client/pull/360) — feat: implement `log/get-level` API — `log.getLevel()` retrieves current log levels without modifying them; uses Kubo `log/level` endpoint with single-arg parameter; full TypeScript types and tests. Closes [#339](https://github.com/ipfs/js-kubo-rpc-client/issues/339).

**libp2p/js-libp2p**

- 🟢 [`#3374`](https://github.com/libp2p/js-libp2p/pull/3374) — feat: track protocol stream open/close count in metrics — adds `libp2p_protocol_streams_opened_total` and `libp2p_protocol_streams_closed_total` counters alongside the existing gauge, enabling Prometheus `rate()` / `increase()` stream throughput analysis

</details>

---


###
<br>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=patrick-ehimen&show_icons=true&theme=radical" height="180em" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=patrick-ehimen&show_icons=true&locale=en&layout=compact&theme=radical" height="180em" />
</p>

<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=3B82F6&height=70&section=footer"/>
