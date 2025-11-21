# 🚀 Bot Setup Instructions

---

## Table of Contents

* [Prerequisites](#prerequisites)
* [Installation Steps](#installation-steps)
* [Configuration Files](#configuration-files)
* [Running the Bot](#running-the-bot)
* [Contact and Support](#contact-and-support)

---

<details>
<summary><strong>1. Prerequisites</strong> — click to expand</summary>

### Prerequisites

Before running the bot, make sure you have the following installed:

* **Node.js** (Version: `22.11.0`)
* **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

**Tip:** Double-click `setup.bat` (Windows) or `setup.sh` (Linux/macOS) to run an automated setup — *remember to fill all required fields first*.

</details>

<details>
<summary><strong>2. Installation Steps</strong> — click to expand</summary>

### Installation Steps

1. **Download and Extract the Bot Files:**

   * Extract the bot package into a folder on your computer.

2. **Install Dependencies:**
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

```bash
npm install user-agents axios meo-forkcy-colors meo-forkcy-utils meo-forkcy-proxy meo-forkcy-logger crypto-js ws
```

3. **Prepare Configuration Files:**

   * Ensure all configuration files are set up correctly before running the bot (see the Configuration Files section).

</details>

<details>
<summary><strong>3. Configuration Files</strong> — click to expand</summary>

### Configuration Files

Below each file is given a short description and an example. Expand the file you need.

<details>
<summary><strong>3.1 `configs.json`</strong> — click to expand</summary>

This file controls the bot’s behavior. Example:

```json
{
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100
}
```

* **Fields Explained:**

  * `rotateProxy`: Enable/disable proxy rotation.
  * `skipInvalidProxy`: Skip invalid proxies if `true`.
  * `proxyRotationInterval`: Time interval (minutes) for rotating proxies.
  * `delayEachAccount`: Random delay range (seconds) between accounts.
  * `timeToRestartAllAccounts`: Time (seconds) to restart all accounts.
  * `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.

</details>

<details>
<summary><strong>3.2 `datas.txt`</strong> — click to expand</summary>

* Fill the `datas.txt` file with account data (one row per account). Example entries are base64-like tokens (get from provided source):

```txt
ey...
ey...
ey...
```

*Source:* [https://t.me/KeoAirDropFreeNee/1522](https://t.me/KeoAirDropFreeNee/1522)

</details>

<details>
<summary><strong>3.3 `wallets.txt`</strong> — click to expand</summary>

* Add your wallet addresses (one per line):

```txt
abc...xyz
abc...xyz
abc...xyz
```

*Wallet generator:* [https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

> Note: Wallet updates are currently not supported.

</details>

<details>
<summary><strong>3.4 `proxies.txt`</strong> — click to expand</summary>

If you are using proxies, add them here (one row per account). Leave blank if you are not using proxies. Supported formats:

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

</details>

</details>

<details>
<summary><strong>4. Running the Bot</strong> — click to expand</summary>

### Running the Bot

1. Navigate to the folder containing the bot files:

```bash
cd /path/to/stream-ai
```

2. Run the bot:

```bash
node meomundep.js
```

</details>

<details>
<summary><strong>5. Contact and Support</strong> — click to expand</summary>

* **Help me with your referral:** [Referral Link](https://app.allstream.ai/index?referralCode=jhnJinLO)
* **Buy me a telegram account:** [Link A](https://t.me/KeoAirDropFreeNe/312/27801) • [Link B](https://github.com/MeoMunDep/MeoMunDep)

If you encounter issues, contact:

* **Contact:** [Contact Me](https://t.me/MeoMunDep)
* **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
* **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Your support is appreciated! 🐱

</details>

⚠️ **Disclaimer**

This project was created solely as a **personal educational exercise**.  
It is **not an official product**, website, or service of any company or brand referenced in this repository.  
The creator is **not affiliated, associated, endorsed by, or connected** with any such company or brand in any way.

The code is provided **"as is"** without any warranties or guarantees.  
Certain parts of the source are intentionally **obfuscated** to protect personal research, custom logic, and implementation techniques developed during learning and experimentation.

Use this project responsibly and at your own risk.  
**Redistribution, resale, or commercial use** of any part of this code—whether original or modified—is **not permitted**.
