# Meme Intelligence & Launch Scout

**Name:** meme-launch-scout  
**Version:** 1.0  
**Author:** devdavidll  
**Description:** Professional real-time meme intelligence agent. Detects trending memes early, performs deep rug risk analysis, and generates complete professional launch kits ready for Clanker, Doppler or other launchers.

## Overview
This skill combines on-chain forensics, real-time social sentiment analysis (X + Farcaster), and DexScreener data to deliver actionable meme coin intelligence. It helps users find high-potential memes while minimizing rug risk and provides everything needed to launch safely and effectively.

## Core Capabilities

- `scout-memes [timeframe]` — Scans and ranks the hottest emerging memes (Last 1h / 6h / 24h).
- `deep-analyze [token address / ticker / contract]` — Complete due diligence report including:
  - Liquidity lock status
  - Dev / sniper wallet analysis
  - Holder concentration
  - Social sentiment score
  - Rug risk rating (Low / Medium / High)
- `generate-launch-kit [meme concept]` — Creates a full professional launch package:
  - Recommended token parameters
  - Bonding curve suggestion
  - Viral Twitter thread + image generation prompts
  - Hype strategy and timeline
- `monitor [keywords or address]` — Sets up persistent monitoring with Telegram/Discord alerts.
- `portfolio-meme-scan` — Analyzes all meme tokens in the connected wallet.

## Usage Examples

- "Scout the hottest memes right now on Base"
- "Deep analyze 0x123abc... and give me the risk score"
- "Generate a complete launch kit for a chill frog smoking a cigar meme"
- "Monitor $PEPE and similar tokens"

## Safety & Guardrails (Very Important)

- **No automatic transactions**: This skill never executes buys, launches, or any on-chain action without explicit user confirmation.
- Always shows full risk assessment before recommending any action.
- Uses Bankr wallet **only** after clear user approval ("yes" or "confirm").
- Rate limiting on heavy scans to prevent abuse.
- Never shares private keys or sensitive wallet information.
- All generated content is clearly marked as educational / informational.

## Dependencies
- Bankr Core
- X / Farcaster integration
- DexScreener / On-chain data providers

## How to Use with Bankr
1. Install this skill
2. Talk naturally to your agent (examples above)
3. Always review risk reports before taking action

## Disclaimer
This skill is for informational and entertainment purposes. Crypto and meme coins are highly volatile and risky. Always do your own research (DYOR). The skill helps reduce risk but does not eliminate it.

---
**Ready for production use.**
