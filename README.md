# Bot Trading cbBTC/USDC — Race 24 Jam

[![Kompetisi btc-race-24h-20261118-1444](https://make.fun/badge/btc-race-24h-20261118-1444.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444)
[![Peringkat](https://make.fun/badge/btc-race-24h-20261118-1444/swaetczher/btc-race-24h-20261118-1444/rank.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444)
[![Hadiah](https://make.fun/badge/btc-race-24h-20261118-1444/swaetczher/btc-race-24h-20261118-1444/reward.svg)](https://make.fun/bounty/btc-race-24h-20261118-1444)

Bot trading yang memperdagangkan cbBTC/USDC menit per menit dengan uang
paper (modal awal 1.000 USDC) melawan harga on-chain nyata, dibuat untuk
kompetisi [btc-race-24h-20261118-1444 di make.fun](https://make.fun/bounty/btc-race-24h-20261118-1444).

## Cara jalan

```sh
python3 main.py
```

Program hanya memakai pustaka standar Python (stdlib-only) — tanpa
dependensi luar, tanpa jaringan saat jalan.

## File

- `main.py` — entrypoint bot: membaca satu baris JSON per menit dan
  menjawab dengan order beli/jual
