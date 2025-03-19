# Crypto Wallet Simulator

A lightweight, local tool to create fake cryptocurrency wallet screenshots for scambaiting. Designed to waste scammers' time by mimicking real wallet interfaces with customizable balances, transfers, and themes—no real money or blockchain involved.

Live demo: [https://melvynandrew99.github.io/CryptoWalletSimulator/](https://melvynandrew99.github.io/CryptoWalletSimulator/)

Repo: [https://github.com/MelvynAndrew99/CryptoWalletSimulator](https://github.com/MelvynAndrew99/CryptoWalletSimulator)

## Purpose

Scammers often demand wallet screenshots to "verify" transactions. This tool lets you procrastinate and disrupt their schemes by generating believable fakes. It’s not perfect—scammers aren’t either when they’re hooked. Built to run locally, it avoids the hassle of test blockchains (which need token requests) and keeps things simple. Expect updates as scammer tactics evolve!

## Warning

**This tool is intended solely for scambaiting—to waste the time of scammers who target you. Do not use it for illegal activities, fraud, or to deceive anyone other than scammers. Misuse could lead to legal consequences, and the author is not responsible for improper use.**

## Features

- **Fake Wallet Balance**: Click the BTC or USD amount to edit, updates both values automatically using live BTC prices (or a fallback rate).
- **Send Fake BTC**: Enter an amount, "send" it, and watch the wallet balance decrease—perfect for screenshot sequences.
- **Custom App Name**: Click the title (e.g., "Cashe App") to rename it—make it your own.
- **Theme Switching**: Use `←` and `→` arrow keys to cycle through four themes:
  - Default (Cash App-inspired)
  - Coinbase-like
  - Binance-like
  - 90s Retro (for fun)
- **Persistence**: Balance, app name, and theme save to `localStorage`—refresh and they stick.
- **Live BTC Price**: Fetches current BTC/USD rate from CryptoCompare (falls back to ~$83,777 if offline).
- **Screenshot-Ready**: Modern header design with gradients and shadows for a legit look.

## How to Use

### Online
1. Visit [https://melvynandrew99.github.io/CryptoWalletSimulator/](https://melvynandrew99.github.io/CryptoWalletSimulator/).
2. Customize:
   - Click the title to edit the app name.
   - Click the BTC or USD balance to set your wallet amount.
   - Enter an amount in "Send BTC" and click the button to "transfer" (reduces balance).
   - Press `←`/`→` to switch themes.
3. Take a screenshot to bait scammers!

### Local
1. Clone or download from [https://github.com/MelvynAndrew99/CryptoWalletSimulator](https://github.com/MelvynAndrew99/CryptoWalletSimulator).
2. Open `index.html` in a browser (double-click it).
3. Follow the same customization steps as above.

**Note**: Runs entirely in your browser—no server or real transactions involved.

## Contributing

This is a living tool—scammers change, so will we. Feel free to:
- Fork the repo and tweak themes in the `styles/` folder.
- Suggest new features via issues.
- Submit PRs for new themes or improvements.

Keep it simple—edit a CSS file or tweak the JS in `index.html`. No complex setup needed!

## License

Public domain—use it, share it, mess with scammers however you like, but only for scambaiting purposes as outlined in the warning.
