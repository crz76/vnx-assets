
# VNX Assets

Public assets for VNX (logos + tokenlist). Host here and use raw URLs in wallets/DEX/trackers.

## Files
- `vnx_logo_32.svg` → 32×32 SVG (Etherscan logo requirement)
- `vnx_logo_256.png` → recommended logo for token lists
- `vnx_logo_1024.png` → large logo
- `vnx-tokenlist.json` → Uniswap-compatible token list

## Raw URLs
- SVG 32: https://raw.githubusercontent.com/crz76/vnx-assets/main/vnx_logo_32.svg
- PNG 256: https://raw.githubusercontent.com/crz76/vnx-assets/main/vnx_logo_256.png
- PNG 1024: https://raw.githubusercontent.com/crz76/vnx-assets/main/vnx_logo_1024.png
- Tokenlist: https://raw.githubusercontent.com/crz76/vnx-assets/main/vnx-tokenlist.json

## Token Info
- Chain: Ethereum Mainnet (chainId 1)
- Token Address: `0x27BB16f90E4B007c51430d1c76152Ad6B5E8fD41`
- Decimals: 18
- Symbol: VNX

## Use in Uniswap
1. Open Uniswap app → Settings → Token Lists.
2. Add list → paste: `https://raw.githubusercontent.com/crz76/vnx-assets/main/vnx-tokenlist.json`.
3. Enable the VNX list.

## Etherscan form
- Official Website: use GitHub Pages for free (e.g. https://crz76.github.io/vnx-site/)
- Email: public email displayed on the site (e.g. vnxtokenproject@gmail.com)
- Logo field: use the SVG 32 URL above.

## Notes
- Update the tokenlist version (semver) when you change contents.
- Keep image sizes small (<100KB for PNG 256, SVG minimal).
