# Encour

## Overview
**Encour** (Verifiable AI-Assisted Decentralized Trading) is a powerful, AI-powered trading assistant reimagined as a **Farcaster-native mini-app** running entirely on **Celo** — the most mobile-friendly, low-cost EVM chain.

Designed for crypto traders inside Warpcast, Encour delivers real-time market insights, whale intelligence, AI-powered trade recommendations, and verifiable onchain trade validation — all within a seamless, beautiful Farcaster Frame → Mini-App experience.

By combining Celo’s instant finality and near-zero fees with Farcaster’s social graph and viral distribution, Encour makes professional-grade trading tools accessible to everyone, directly inside their favorite social feed.

## What It Does
Encour brings institutional-level trading intelligence into Farcaster:

- **Real-Time Market Data** – Live prices for BTC, ETH, and top tokens on Celo
- **Whale Intelligence** – Tracks and classifies whale moves (Mega Whales → Fish) in real time
- **AI Trading Assistant** – Personalized trade ideas, risk/reward ratios, and entry/exit signals
- **Onchain Trade Validation** – Every recommendation can be validated and executed transparently on Celo
- **SocialFi Layer** – Share winning strategies, follow top traders, tip in cUSD/cEUR, and build reputation — all inside Warpcast

## The Problem It Solves
Most traders live in Farcaster but have to leave the app to access quality trading tools. Encour eliminates context switching: you discover alpha in a cast → open Encour Frame → get AI insights → execute on Celo → share results — without ever leaving Warpcast.

## Technologies Used
- **Frontend**: Next.js 14 (App Router), Tailwind CSS, TypeScript, shadcn/ui
- **Social Layer**: Farcaster Frames v2 → Mini-App spec, Neynar API, Warpcast-optimized embedding
- **Blockchain**: Celo Mainnet & Alfajores, wagmi + viem, RainbowKit-Celo
- **Wallet**: Native Celo wallet connect (Valora, Rainbow, etc.)
- **AI**: Lightweight on-device + cloud inference optimized for speed inside mobile WebViews
- **Data**: Coingecko, Celo blockchain indexing, onchain event listening
- **Deployment**: Vercel (Edge Functions for sub-second load times)

## How We Built It
1. Started with the original VAAD AI-0G vision on 0G
2. Realized Farcaster + Celo is the perfect home for social trading
3. Rebuilt everything as a production-grade Farcaster mini-app
4. Optimized every millisecond for instant loading inside Warpcast
5. Leveraged Celo’s speed and low fees for seamless onchain interactions
6. Tested extensively with real traders inside Warpcast

## Roadmap

### Wave 1: Launch & Core Intelligence (Now Live)
- Farcaster Frame entrypoint → full mini-app
- Real-time price feeds + whale tracking
- AI assistant with risk/reward calculations
- Celo wallet connect & transaction support

### Wave 2: Social Trading Layer
- Follow top traders on Farcaster
- One-tap copy trading (onchain)
- Tip successful signal providers in cUSD
- Reputation scores based on verified PnL

### Wave 3: Advanced AI & Analytics
- Personalized strategy engine based on user history
- Predictive regime detection (bull/bear/choppy)
- Portfolio tracking across Celo DeFi

### Wave 4: Community Governance
- Encour DAO token (on Celo)
- Community-curated signal channels
- Revenue share for top performers

## Challenges We Overcame
- Making complex trading data beautiful and fast inside a mobile WebView
- Achieving <1s load time when opened from a Frame
- Handling dynamic viewport/keyboard issues in Warpcast
- Building reliable whale detection without centralized oracles

## What We Learned
- Farcaster is the new Bloomberg terminal for crypto
- Celo + Farcaster is the most powerful (and underrated) stack for social finance
- Traders will adopt tools that live where they already spend 5+ hours a day

## What's Next for Encour
- Launch copy-trading with verified onchain PnL
- Partner with top Farcaster power users for exclusive channels
- Add support for perpetuals and options via Celo DeFi protocols
- Build the first truly social, verifiable trading terminal


(Works instantly on mobile — no app download required)

## Installation (for developers)
```bash
git clone https://github.com/Valortin/Encour.git
cd Encour
npm install
cp .env.example .env.local
# Add your Neynar API key and Alchemy/Infura Celo endpoint
npm run dev
```

## Contributing
We’re building the future of social trading in public. Contributions very welcome!  
Especially: better AI models, new whale detection heuristics, beautiful chart components.

## License
MIT — build on it, fork it, ship it.

## Contact
- **Creator**: Valortin (@valortin on Farcaster & Twitter)
- **GitHub**: https://github.com/Valortin
- **Warpcast**: https://warpcast.com/valortin

## Acknowledgments
- The incredible Farcaster and Celo teams
- Early alpha testers who gave brutally honest feedback
- Everyone building the onchain social future

**Encour — where alpha lives.**  
Trade smarter. Stay in the cast. Never leave the conversation.