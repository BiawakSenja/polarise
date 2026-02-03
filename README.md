# polarise
# 🚀 Polarise BOT (Paid BOT)

> An all-in-one automation bot for the Polarise ecosystem, streamlining on-chain interactions, task farming, content engagement, and multi-account operations.

[![Python Version](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/vonssy/Polarise-BOT.svg)](https://github.com/vonssy/Polarise-BOT/stargazers)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [Proxy Recommendation](#proxy-recommendation)
- [Support](#support)
- [Contributing](#contributing)

## 🎯 Overview

An automated on-chain interaction bot for the Polarise ecosystem, designed to handle daily tasks, wallet activities, content creation, and point-to-token conversions across multiple accounts — with full proxy support and smart automation logic.

**🔗 Get Started:** [Register on Polarise](https://app.polarise.org/?code=2BHlBH)

> **Important:** Sign-Up With New EVM Wallet.

## ✨ Features

- 🔄 **Automated Account Management** - Retrieve account information automatically
- 🌐 **Flexible Proxy Support** - Run with or without proxy configuration
- 🔀 **Smart Proxy Rotation** - Automatic rotation of invalid proxies
- 💰 **Testnet Tokens Claims** - Automated testnet tokens claiming
- 🔁 **Swap Points to GRISE** – Automatically convert earned points into GRISE tokens  
- 🔓 **Address Activation** – Automatically activate wallet/address when required  
- 🔗 **Daily On-Chain Interaction** – Perform daily on-chain interactions automatically to maintain activity  
- 💬 **Create Discussion** – Automatically create discussions on the platform  
- 📝 **Create Post** – Automatically publish posts  
- 💸 **Send Tip** – Automatically send tips to other users  
- 💭 **Post Comment** – Automatically post comments on discussions or posts  
- 📡 **Subscribe to Others** – Automatically subscribe to other users  
- ✅ **Complete Other Task** – Automatically complete remaining tasks *(excluding Gmail connection)*  
- 👥 **Multi-Account Support** - Manage multiple accounts simultaneously

## 🏷️ Price
- **Price:** $7 in Cryptocurrency
- **Contact:** [Vonssy](https://t.me/vonssy_2nd)

## 📋 Requirements

- **Python:** Version 3.9 or higher
- **pip:** Latest version recommended
- **Compatible libraries:** web3, eth-account, eth-utils, eth-abi (see requirements.txt)
- **Grok Ai API Key:** For automated create discussion & post
- **2captcha API Key:** For automated google recaptcha solving

## 🛠 Installation

### 1. Extract The Zip File

```bash
unzip Polarise-BOT
cd Polarise-BOT
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
# or for Python 3 specifically
pip3 install -r requirements.txt
```

### 3. Library Version Management

> ⚠️ **Important:** Ensure library versions match those specified in `requirements.txt`

**Check installed library version:**
```bash
pip show library_name
```

**Uninstall conflicting library:**
```bash
pip uninstall library_name
```

**Install specific library version:**
```bash
pip install library_name==version
```

## ⚙️ Configuration

### Config Setup

Create or edit `grok_api_key.txt` in the project directory:

```
your_grok_api_key_1
your_grok_api_key_2
your_grok_api_key_3
```

### Account Setup

Create or edit `accounts.txt` in the project directory:

```
your_evm_private_key_1
your_evm_private_key_3
your_evm_private_key_2
```

### Proxy Configuration (Optional)

Create or edit `proxy.txt` in the project directory:

```
# Simple format (HTTP protocol by default)
192.168.1.1:8080

# With protocol specification
http://192.168.1.1:8080
https://192.168.1.1:8080

# With authentication
http://username:password@192.168.1.1:8080
```

## 🚀 Usage

Run the bot using one of the following commands:

```bash
python bot.py
# or for Python 3 specifically
python3 bot.py
```

### Runtime Options

When starting the bot, you'll be prompted to choose:

1. **Proxy Mode Selection:**
   - Option `1`: Run with proxy
   - Option `2`: Run without proxy

2. **Auto-Rotation:** 
   - `y`: Enable automatic invalid proxy rotation
   - `n`: Disable auto-rotation

## 💖 Support the Project

If this project has been helpful to you, consider supporting its development:

### Cryptocurrency Donations

| Network | Address |
|---------|---------|
| **EVM** | `0xe3c9ef9a39e9eb0582e5b147026cae524338521a` |
| **TON** | `UQBEFv58DC4FUrGqinBB5PAQS7TzXSm5c1Fn6nkiet8kmehB` |
| **SOL** | `E1xkaJYmAFEj28NPHKhjbf7GcvfdjKdvXju8d8AeSunf` |
| **SUI** | `0xa03726ecbbe00b31df6a61d7a59d02a7eedc39fe269532ceab97852a04cf3347` |

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. ⭐ **Star this repository** if you find it useful
2. 👥 **Follow** for updates on new features
3. 🐛 **Report issues** via GitHub Issues
4. 💡 **Suggest improvements** or new features
5. 🔧 **Submit pull requests** for bug fixes or enhancements

## 📞 Contact & Support

- **Developer:** vonssy
- **Issues:** [GitHub Issues](https://github.com/vonssy/Polarise-BOT/issues)
- **Discussions:** [GitHub Discussions](https://github.com/vonssy/Polarise-BOT/discussions)

---

<div align="center">

**Made with ❤️ by [vonssy](https://github.com/vonssy)**

*Thank you for using Polarise BOT! Don't forget to ⭐ star this repository.*

</div>
