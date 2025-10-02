# Pragma Documentation Monorepo

<p align="center">
  <img src="https://github.com/astraly-labs/pragma-docs/raw/main/docs/static/img/pragma-og-img.svg" alt="Pragma Logo" width="200"/>
</p>

> This repository contains the documentation for Pragma Oracle and 0D Finance, built with [Mintlify](https://mintlify.com).

## 📚 Documentation Sites

This monorepo contains two separate Mintlify documentation projects:

### 🔮 Pragma Oracle (`/pragma`)
Pragma is the decentralized, transparent and composable oracle network, leveraging state-of-the-art zero-knowledge cryptography.

**What's covered:**
- 🧮 **Computational Feeds**: Advanced data processing capabilities
- 🎲 **Randomness**: Secure, verifiable random number generation
- 🏛️ **Architecture**: Technical infrastructure deep-dive
- 🔌 **Pragma API**: Integration guides for StarkNet, StarkEx, and Offchain data

### 💰 0D Finance (`/0d-finance`)
0D Finance documentation covers vault management, liquidity, performance metrics, and user interactions.

**What's covered:**
- 🏦 **Vaults**: Vault operations and management
- 📊 **Performance**: Historical data and KPIs
- 💧 **Liquidity**: Slippage curves and withdrawal simulations
- 📈 **APR & Composition**: Returns and asset allocation
- 👤 **User Operations**: Profile, positions, and transactions

## 🚀 Local Development

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Mintlify CLI

### Setup
```bash
# Install Mintlify CLI
npm i -g mintlify

# Run Pragma docs locally
cd pragma
mintlify dev

# Or run 0D Finance docs locally
cd 0d-finance
mintlify dev
```

## 📁 Repository Structure

```
.
├── pragma/              # Pragma Oracle documentation
│   ├── docs.json        # Pragma navigation & config
│   ├── api-reference/   # API documentation
│   ├── starknet/        # StarkNet integration guides
│   └── open-apis/       # OpenAPI specifications
│
├── 0d-finance/          # 0D Finance documentation
│   ├── docs.json        # 0D Finance navigation & config
│   ├── 0d/              # Core 0D content
│   ├── api-reference/   # 0D API documentation
│   └── open-apis/       # OpenAPI specifications
│
└── README.md            # This file
```

## 🔗 Useful Links

### Pragma
- 🌐 [Website](https://pragma.build)
- 📱 [Twitter](https://x.com/PragmaOracle)
- 📝 [Blog](https://blog.pragma.build)
- 💬 [Discord](https://discord.com/invite/M9aRZtZHU7)
- 🐙 [GitHub](https://github.com/astraly-labs)

### 0D Finance
- 🌐 [Website](https://0d.finance)
- 💬 [Community](https://t.me/+Xri-uUMpWXI3ZmRk)

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This documentation is licensed under [MIT License](LICENSE).

---

Happy building! 🎉
