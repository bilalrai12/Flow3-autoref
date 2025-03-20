# Flow3 Network Auto Referral

This bot automates the process of creating accounts and using referral codes for the Flow3 Website

## Features

- Automatically generates wallet.
- Uses proxies to avoid IP bans.
- Logs the created accounts.

## Requirements

- Node.js v18.20.6 LTS [Download](https://nodejs.org/dist/v18.20.6/node-v18.20.6-x64.msi).
- Account Flow3 [Flow3](https://dashboard.flow3.tech?ref=3cLxQoe5j)
- Proxy (Optional). Best Proxy [Cherry Proxy](https://center.cherryproxy.com/Login/Register?invite=029ad2d3)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/ahlulmukh/flow3-autoref.git
   cd flow3-autoref
   ```

2. Install the dependencies:

   ```sh
   npm install
   npm run build
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line).
   ```
   http://user:pass@host:port
   http://user:pass@host:port
   http://user:pass@host:port
   ```

## Usage

1. Run the bot:

   ```sh
   npm run start
   ```

2. Follow the prompts to enter your referral code

## Output

- The created accounts will be saved in `accounts.txt`.

## Notes

- Make sure to use valid proxies to avoid IP bans.

## Stay Connected

- Channel Telegram : [Telegram](https://t.me/Bilalstudio2)
-
## Disclaimer

This tool is for educational purposes only. Use it at your own risk.
