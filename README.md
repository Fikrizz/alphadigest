# 📡 AlphaDigest

> AI crypto news & announcement decoder

Paste any crypto news, tweet, or announcement. Get TL;DR, affected assets, beneficiaries, skepticism flags, and what to watch next.

## ✨ Features

- TL;DR + sentiment + confidence rating per signal
- Affected assets with impact direction (positive/negative/neutral)
- Beneficiaries vs losers analysis
- Skepticism flags — what to verify, what's sus
- Time-sensitivity classification (immediate/days/weeks/long-term)
- Perspective-aware: trader gets trade theses, builder gets engineering lessons
- Historical parallel for context
- 6 source types: tweet / news / official / blog / leaked / on-chain
- Multi-language UI (English / 中文)
- BYOK Xiaomi MiMo API support with free Pollinations fallback
- Zero dependencies, single-file HTML

## 🚀 Quick Deploy

### Vercel (drag-drop, paling cepat)
1. Buka [vercel.com/new](https://vercel.com/new)
2. Drag folder `alphadigest/` ke area drop
3. Klik Deploy. URL hidup dalam 30 detik.

### Local
```bash
cd alphadigest
python3 -m http.server 8000
# buka http://localhost:8000
```

## 🔑 Setup MiMo API Key (recommended)

1. Klik **⚙** di header
2. Paste API key dari [api.xiaomimimo.com](https://api.xiaomimimo.com)
3. Test Connection → Save

Tanpa API key, app pakai Pollinations free endpoint (terbatas, demo only).

## 🏗️ Stack

- Single-file HTML, vanilla JS, zero dependencies
- Xiaomi MiMo V2.5 (primary) → Pollinations (fallback)
- localStorage untuk settings, no server

## 📦 Built for

[**MiMo 100T Creator Program**](https://100t.xiaomimimo.com)

## 📄 License

MIT — fork, modify, gunakan komersial bebas.

---

Made by [@Fikrizz](https://github.com/Fikrizz) · Powered by Xiaomi MiMo
