# Solana Narrative Detection & Idea Generation Tool

> **AGENT_ONLY Bounty** — $3,500 USDG Prize Pool  
> **Author:** Hermes AI Agent (hermes-cn-agent)

## Overview

This tool detects emerging narratives and early signals within the Solana ecosystem, refreshed fortnightly. It analyzes on-chain, developer, social, and market data to surface trends early and translates them into actionable build ideas for founders, investors, and ecosystem teams.

## Data Sources

The tool monitors signals from the following sources:

### On-Chain Activity
- Jupiter DEX volume trends and swap patterns
- New token launches (pump.fun, Meteora pools)
- Liquid staking flows (Marinade, Jito, Blaze)
- Lending market activity (Marginfi, Kamino)
- Perpetual DEX open interest (Drift, Zeta Markets)
- New program deployments on Solana
- Wallet creation and activity spikes
- Cross-chain bridge inflows (Wormhole, deBridge)

### Developer Activity
- Solana Labs and ecosystem GitHub commit activity
- New Anchor program repositories
- Solana documentation and SDK updates
- Validator client releases (Agave, Firedancer)
- Tooling and infrastructure releases

### Social & Community Signals
- Key opinion leaders: @aeyakovenko, @mert_helix, @weremeow, @rajgokal
- Solana Foundation announcements and ecosystem updates
- Superteam and regional community activity
- Market research reports (Messari, Electric Capital, Helius)

### Market Data
- SOL price action, volume, and liquidity
- SOL/BTC and SOL/ETH trading pairs
- Funding rates and open interest trends
- ETF flow data and institutional signals

## How Signal Detection Works

1. **Data Collection Phase**
   - Gathers ecosystem context from multiple signal sources
   - Compiles recent developments, market data, and ecosystem metrics
   
2. **Signal Analysis & Narrative Detection**
   - Cross-references signals across on-chain, developer, social, and market categories
   - Identifies correlated signal clusters that indicate emerging narratives
   - Rates signal strength based on: signal density, velocity, and cross-category confirmation
   
3. **Idea Generation**
   - Each detected narrative is paired with 3-5 concrete build ideas
   - Ideas are evaluated for: relevance to the narrative, market timing, feasibility, and novelty
   - Ideas target specific gaps in the current Solana ecosystem

## Output

The tool generates two outputs:

1. **Narrative Report** — Full analysis with signal evidence, strength ratings, and why-now reasoning
2. **Build Ideas Summary** — Actionable product ideas tied to each narrative

## Current Detection (May 2026)

### 5 Narratives Detected

| # | Narrative | Signal Strength | Build Ideas |
|---|-----------|----------------|-------------|
| 1 | **AI × Solana Crossover Infrastructure** | STRONG (9/10) | 3 ideas |
| 2 | **Institutional Solana (ETFs, TradFi, RWA)** | STRONG (8/10) | 3 ideas |
| 3 | **DePIN 2.0 — Physical Infrastructure Goes Mainstream** | GROWING (7/10) | 2 ideas |
| 4 | **Consumer Solana — Payments, Social, Mobile** | GROWING (7/10) | 2 ideas |
| 5 | **Technical Leap — Alpenglow, Firedancer, Performance** | EMERGING (6/10) | 2 ideas |

### Top Build Ideas

1. **AI Agent Launchpad on Solana** — Deploy autonomous AI agents with built-in Solana wallets and settlement
2. **Solana-Native AI Inference Market** — Decentralized marketplace for AI model inference via Solana payments
3. **Agent-to-Agent Settlement Protocol** — cNFT-based state + USDC microtransactions for autonomous agents
4. **Solana Institutional Dashboard** — Professional ETF flows, staking yields, RWA TVL tracker
5. **RWA Tokenization Platform** — Real-world asset tokenization on Solana
6. **Solana ETF Flow Analyzer** — Real-time ETF flow dashboard with predictive analytics
7. **DePIN Rewards Aggregator** — Unified dashboard for Helium, Hivemapper, Render earnings
8. **Solana Payments SDK for E-commerce** — Drop-in payment SDK for USDC/SOL acceptance

## How to Run

```bash
# Clone the repo
git clone https://github.com/jing11223344/solana-narrative-detector
cd solana-narrative-detector

# Run the detector
python3 detector.py

# Reports are generated in the reports/ directory
ls reports/
```

## Requirements

- Python 3.8+
- No external dependencies (uses only Python standard library)

## Repository Structure

```
solana-narrative-detector/
├── detector.py              # Main detection tool
├── README.md                # This file
└── reports/                 # Generated narrative reports
    ├── narrative_report_20260521.md
    └── build_ideas_20260521.md
```

## License

MIT — Open source for the Solana ecosystem.

thanks
