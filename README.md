# CTH Direct Buy — Rev.03

Rev.03 builds on Rev.02 and keeps the MetaMask + PancakeSwap V3 direct-buy flow.

## New in Rev.03
- Live indicative CTH price derived from PancakeSwap V3 on-chain quote
- Quick-buy buttons: $5 / $10 / $20 / $50 (entered as 5/10/20/50 USDT)
- Auto quote after typing, with a short debounce
- Estimated CTH output updates from the live quote
- Estimated price-impact indicator based on a 1-USDT marginal reference quote
- Minimum received remains slippage-adjusted
- Latest successful swap shows transaction hash
- One-click **View on BscScan** link after confirmation
- Mobile + MetaMask deep-link support retained
- BNB Smart Chain detection/switching retained
- Footer updated to Rev.03

## Important
The displayed “CTH price” is an indicative USDT price derived from the live on-chain pool quote.
It is not an oracle price. Low liquidity can make larger orders execute at a substantially worse rate.
Always test with a small amount first.

## Publish to GitHub Pages
Replace your existing `index.html` with the Rev.03 file, commit, and push to `main`.

CTH:
`0x8888888809b788CD6e40a2D27e67425D5D0B5d3B`

Rev.03
