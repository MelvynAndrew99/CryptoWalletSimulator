# Crypto Wallet and Payment Simulators

A collection of lightweight, local tools to create fake cryptocurrency wallet and payment app screenshots for scambaiting. Designed to waste scammers' time by mimicking real interfaces with customizable data—no real money or transactions involved.

## Available Simulators

- **Crypto Wallet Simulator**: [https://melvynandrew99.github.io/CryptoWalletSimulator/](https://melvynandrew99.github.io/CryptoWalletSimulator/) - Simulate Crypto Payments
- **Cash App Simulator**: [https://melvynandrew99.github.io/CryptoWalletSimulator/cash.html](https://melvynandrew99.github.io/CryptoWalletSimulator/cash.html) - Simulate Cash Payments

Repo: [https://github.com/MelvynAndrew99/CryptoWalletSimulator](https://github.com/MelvynAndrew99/CryptoWalletSimulator)

## Purpose

Scammers often demand wallet screenshots or payment confirmations to "verify" transactions. These tools let you procrastinate and disrupt their schemes by generating believable fakes. Built to run locally, they avoid the hassle of test blockchains and keep things simple. Expect updates as scammer tactics evolve!

## Warning

**These tools are intended solely for scambaiting—to waste the time of scammers who target you. Do not use them for illegal activities, fraud, or to deceive anyone other than scammers. Misuse could lead to legal consequences, and the author is not responsible for improper use.**

## Crypto Wallet Simulator Features

- **Fake Wallet Balance**: Click the BTC or USD amount to edit, updates both values automatically using live BTC prices (or a fallback rate).
- **Send Fake BTC**: Enter an amount, "send" it, and watch the wallet balance decrease—perfect for screenshot sequences.
- **Custom App Name**: Click the title (e.g., "Cashe App") to rename it—make it your own.
- **Theme Switching**: Use `←` and `→` arrow keys to cycle through different themes.
- **Persistence**: Balance, app name, and theme save to `localStorage`—refresh and they stick.
- **Live BTC Price**: Fetches current BTC/USD rate from CryptoCompare (falls back to ~$83,777 if offline).
- **Screenshot-Ready**: Modern header design with gradients and shadows for a legit look.

## Cash App Simulator Features

- **Multiple Payment States**: Toggle between Pending, Completed, and Fraud alert screens using left/right arrow keys
- **Editable Fields**: Click on recipient name/number, payment amount, and note to edit them directly
- **Randomized Transaction IDs**: Auto-generates realistic transaction IDs
- **Current Timestamp**: Displays the current time when loaded
- **Hidden Controls**: Press 'H' to show/hide the control panel, 'R' to generate new transaction IDs

Perfect for creating convincing payment screenshots to waste scammers' time while keeping them on the hook.

## How to Use

### Online
1. Visit the links above for either simulator.
2. Customize the details as needed.
3. Take a screenshot to bait scammers!

### Local
1. Clone or download from [https://github.com/MelvynAndrew99/CryptoWalletSimulator](https://github.com/MelvynAndrew99/CryptoWalletSimulator).
2. Open `index.html` or `cash.html` in a browser.
3. Follow the same customization steps as above.

**Note**: Everything runs entirely in your browser—no server or real transactions involved.

## Contributing

These are living tools—scammers change, so will we. Feel free to:
- Fork the repo and tweak themes or functionality.
- Suggest new features via issues.
- Submit PRs for new simulators or improvements.

Keep it simple—edit CSS files or tweak the JS. No complex setup needed!

## License

Public domain—use it, share it, mess with scammers however you like, but only for scambaiting purposes as outlined in the warning.