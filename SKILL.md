# Meme Intelligence & Launch Scout

**Name:** meme-launch-scout  
**Version:** 1.1  
**Author:** devdavidll  
**Description:** Professional real-time meme intelligence and safe launch assistant. Detects emerging trends early, performs deep rug risk analysis, and generates complete production-ready launch kits for Clanker, Doppler and similar platforms.

## Overview
Advanced skill that combines social sentiment analysis (X + Farcaster), on-chain forensics, and DEX data to deliver high-quality meme coin intelligence while maintaining maximum user safety.

## Core Capabilities

- `scout-memes [timeframe]` — Returns ranked list of emerging memes (1h / 6h / 24h).
- `deep-analyze <token address | ticker | name>` — Full due diligence report including liquidity lock, dev/sniper wallets, holder concentration, sentiment, and rug risk rating.
- `generate-launch-kit <meme concept>` — Complete launch package: token parameters, bonding curve, viral Twitter/Farcaster thread, and image prompts.
- `monitor <keywords or address>` — Persistent monitoring with alerts via Telegram/Discord.
- `wallet-meme-scan` — Scans and analyzes meme tokens in the connected Bankr wallet.

## Usage Examples

- "Scout the hottest memes right now on Base"
- "Deep analyze 0x... and give me the risk level"
- "Generate a professional launch kit for a cyberpunk cat meme"
- "Monitor $PEPE and similar tokens"

## Safety & Guardrails

- This skill **never** executes any on-chain transaction without explicit user confirmation.
- Always provides clear risk assessment (Low / Medium / High) before any recommendation.
- Bankr wallet is used **only** after the user explicitly says "confirm", "yes", or "approve".
- Rate limiting implemented to prevent abuse.
- No private keys or sensitive data are ever exposed.
- All content is provided for informational purposes only.

## Dependencies
- Bankr Core
- X Integration
- DexScreener / On-chain data providers

## How to Use
1. Install the skill in Bankr
2. Talk naturally to your agent using the examples above
3. Always review the risk report before taking any action

## Disclaimer
Meme coins are highly volatile and risky. This skill is a tool to help reduce risk through better information, but it does not eliminate risk. Always do your own research (DYOR) and only invest what you can afford to lose.

---
**Ready for production use.**
