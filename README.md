# Onchain Whale Monitor

A Python-based tracker for large cryptocurrency transactions ("whales") on the Bitcoin, Ethereum, Solana blockchains and other Cryptocurrency.  
This tool fetches on-chain transaction data, processes it into a clean format, and prepares it for analysis in Power BI, Excel, or any BI tool.

---

## 🚀 Features
- Fetches whale transactions from:
  - **Ethereum** (via Etherscan API)
  - **Solana** (via Solana API)
  - **Bitcoin** (via Bitcoin API)
  - Additonal to come
- Extracts:
  - Transaction hash
  - Timestamp
  - From / To addresses
  - Transaction direction (Deposit / Withdrawal)
  - Amount in native currency (ETH or SOL)
- Exports data to **CSV** or **Excel** for further analysis
- Ready-to-use for visualization in **Power BI** (e.g., inflow/outflow charts)

---

## 📦 Installation

1. **Clone this repository**  
```bash
git clone https://github.com/YOUR_USERNAME/onchain-whale-monitor.git
cd onchain-whale-monitor
