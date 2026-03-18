# Bridging Assets to Ink

## Overview
CatOnInkChain enables users to bridge assets into Ink using aggregated routes from multiple bridge providers.

## Supported Chains
Users can bridge from:
- Ethereum
- Arbitrum
- Base
- BNB Chain
- Polygon
- Optimism
- Solana
  
## How It Works
1. User selects source chain and token
2. CatOnInkChain queries multiple bridge providers
3. Routes are evaluated based on:
   - Liquidity availability
   - Fees
   - Speed
4. The best route is selected automatically

## Example Flow
Ethereum → Ink:
- User selects ETH/USDC
- Aggregator evaluates routes
- Executes via selected bridge
- Assets arrive on Ink

## Benefits
- No need to manually compare bridges
- Optimized routing
- Faster onboarding into Ink ecosystem
