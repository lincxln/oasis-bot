# OASIS AI BETA CLI VERSION

![banner](image-1.png)
AI inference powered by distributed compute

# Features

![Banner](image.png)

- **Register/Login Accounts**

- **Auto Create Providers**

- **Auto Send Heartbeat**

- **Support Multy Accounts**

- **Support Proxy**

## Requirements

- **Node.js**: Ensure you have Node.js installed.

- **NPM**: Ensure you have npm installed.

put your proxy in file `proxy.txt` format `http://username:pass@ip:port` 1 proxy for 1 provider

so if you want create multiple providers you need to put multiple proxy there.

## Setup

1. Clone this repository:

   ```bash
   git clone https://github.com/adhe222/oasis-bot.git
   cd oasis-bot
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. put your email and pass to `accounts.txt` format `email|password` 1 account for 1 line

   ```bash
   nano accounts.txt
   ```

4. put your proxy to `proxy.txt`

   ```bash
   nano proxy.txt
   ```

5. Setup to create accounts/login and get Tokens:

   ```bash
   npm run setup
   ```

6. Run The Script:

   ```bash
   npm run start
   ```
7. Run autoreff and get token

   ```bash
   npm run autoreff
   ```
source: https://github.com/Zlkcyber/oasis-bot
