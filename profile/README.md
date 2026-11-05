<div align="center">

<img src="https://raw.githubusercontent.com/Blocra-HQ/blocra-frontend/main/public/blocra-logo.png" width="96" alt="BlocRA logo" />

# BlocRA

**Blockchain Resource Analytics: explore on-chain data, build dashboards, and run analytics bounties.**

</div>

---

BlocRA is a blockchain analytics platform. Analysts point it at any contract on 20 supported chains to get
event and transaction analysis, write queries, build shareable dashboards, and export reports. Teams that
need answers can post **bounties** that analysts compete to solve.

## Repositories

| Repo | What it is | Stack |
|------|-----------|-------|
| [**blocra-frontend**](https://github.com/Blocra-HQ/blocra-frontend) | The web app: contract analytics, query editor, dashboard builder, bounties, admin panel | React · TypeScript · Vite · Tailwind |
| [**blocra-backend**](https://github.com/Blocra-HQ/blocra-backend) | The API: auth, bounties, dashboards, saved queries, contract transaction data | Rust · Actix-web · SQLite |
| [**blocra-contracts**](https://github.com/Blocra-HQ/blocra-contracts) | On-chain bounty contract: create, join, submit, select winner | Smart contracts |
| [**blocra-research**](https://github.com/Blocra-HQ/blocra-research) | RPC exploration notebook and on-chain data scripts | Jupyter · Bash |
| [blocra-backend-legacy](https://github.com/Blocra-HQ/blocra-backend-legacy) | The original API, kept for reference; replaced by blocra-backend | Node.js · Express · MongoDB |

## How it fits together

```
          ┌──────────────────────┐        REST /api         ┌──────────────────────┐
 user ──► │   blocra-frontend    │ ───────────────────────► │    blocra-backend    │ ──► SQLite
          │  (Vercel)            │                          │  (Render / Docker)   │
          └─────────┬────────────┘                          └──────────┬───────────┘
                    │ JSON-RPC (multi-endpoint failover)               │ RPC / Alchemy
                    ▼                                                  ▼
        ┌──────────────────────────────────────────────────────────────────────┐
        │  20 chains: EVM networks, Solana, and the bounty contract's chain    │
        └──────────────────────────────────────────────────────────────────────┘
```

## Get involved

Each repo's README covers setup. Issues and pull requests are welcome.
