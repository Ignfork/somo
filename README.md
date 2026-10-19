# Somo ($SOMO)

A single-file website. Upload `index.html` to GitHub Pages, Netlify, Vercel or any host, and it works as-is.

## Edit before launch
At the top of the `<script>` in index.html:

```js
var CONFIG = {
  mint:   '',  // $SOMO mint address: turns on live market stats + real wallet balance checks (never shown on the page)
  buyUrl: '',  // official pump.fun link once live
  xUrl:   'https://x.com/SomoLiveSol',
  tiers:  [...] // Lilac 1+, Violet 100K+, Amethyst 1M+, Royal 10M+ (edit amounts freely)
};
```

## Utility for $SOMO holders
- **Somo Pass**: connect a wallet or paste any address. Somo reads the $SOMO balance and prints a downloadable pass for the tier (Lilac / Violet / Amethyst / Royal). Read-only, nothing to sign.
- **Somo Studio**: a PFP maker with 10 color schemes, 6 eyes, 5 mouths, 7 extras and 7 backgrounds; exports 1000×1000 PNGs. Tagged items unlock by Pass tier once `mint` is set (all unlocked before launch).
- **Market**: live price, market cap, volume, liquidity and buys/sells from DexScreener once `mint` is set.
- **Family**: Somos people make orbit the big one (stored on their own device).
- The hero Somo follows your cursor, blinks, and reacts when clicked.
