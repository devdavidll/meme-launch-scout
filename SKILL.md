# Meme Intelligence & Launch Scout

**Name:** meme-launch-scout  
**Version:** 1.1  
**Author:** devdavidll  
**Description:** Professional real-time meme intelligence and safe launch assistant. Detects emerging trends early, performs deep rug risk analysis, and generates complete production-ready launch kits.

## Overview
Advanced skill that combines social sentiment (X + Farcaster), on-chain forensics, and DEX data to deliver high-quality meme coin intelligence while prioritizing user safety and risk awareness.

## Core Capabilities

- `scout-memes [timeframe]` — Returns ranked list of emerging memes (supports 1h, 6h, 24h).
- `deep-analyze <token address | ticker | name>` — Comprehensive risk report (liquidity lock, dev wallets, holder distribution, sniper activity, sentiment score).
- `generate-launch-kit <meme concept>` — Full launch package including token params, bonding curve recommendation, viral thread, and image prompts.
- `monitor <keywords or address>` — Persistent monitoring with configurable alerts.
- `wallet-meme-scan` — Analyzes meme tokens in the connected Bankr wallet.

## Usage Examples

- "Scout the hottest memes right now on Base"
- "Deep analyze 0x... and tell me the risk level"
- "Generate a professional launch kit for a cyberpunk cat meme"
- "Monitor $GROK and similar tokens"

## Safety & Guardrails

- This skill **never** performs any on-chain transaction (buy, launch, transfer, etc.) without explicit user confirmation.
- Every analysis includes a clear risk rating (Low / Medium / High).
- All launch suggestions are for informational purposes only.
- Bankr wallet is used **only** after the user says "confirm" or "yes".
- Rate limiting and anti-abuse measures implemented.
- Full action logging for transparency.

## Dependencies
- Bankr Core
- X Integration
- DexScreener / On-chain providers

## Disclaimer
Meme coins are extremely volatile and high risk. This tool helps reduce risk through better information but does not eliminate it. Always DYOR and invest only what you can afford to lose.

---
Ready for production.
