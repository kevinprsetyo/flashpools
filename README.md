
---

## 🖥️ User Flow

### 1. Pool List
- Active Flash Pools
- Strategy type
- Expected profit
- Time remaining

### 2. Join Pool
- Input amount
- Estimated share %
- Confirm deposit

### 3. Result
- Profit earned
- Transaction hash
- Pool summary

---

## 💰 Incentive Design

### Users
- Akses arbitrase tanpa bot
- Modal kecil tetap bisa ikut
- Risiko terbatas (atomic execution)

### Strategy Developers
- Mendapat fee dari profit
- Tidak perlu menyediakan modal

### Protocol
- Fee-based revenue
- Network effect dari volume

---

## 💸 Fee Model (Example)

| Recipient | Fee |
|---------|-----|
| Strategy Developer | 10% |
| Protocol | 5% |
| Liquidity Providers | 85% |

> Fee hanya diambil jika transaksi menghasilkan profit.

---

## 🔐 Security Model

### Protections
- Atomic PTB execution
- Slippage & profit threshold
- Strategy whitelisting
- No partial state changes

### Accepted Risks
- Opportunity expired
- Gas fee (minimal)

---

## 🧪 MVP Scope

### Included
- Single arbitrage strategy
- 2 DEX integration
- Manual execution trigger
- On-chain profit distribution

### Excluded (Future)
- Liquidation pools
- Auto execution
- Strategy marketplace
- DAO governance

---

## 🗺️ Roadmap

### Phase 1 – MVP
- FlashPool core contract
- Arbitrage PTB execution
- Basic UI demo

### Phase 2
- Multiple strategies
- Auto execution
- Risk scoring

### Phase 3
- Liquidation pools
- Institutional pools
- DAO governance

---

## 📊 Success Metrics

- Pool fill rate
- Execution success rate
- Average profit per pool
- Unique contributors
- On-chain volume

---

## 🧩 Why Sui

Flash Pools:
- Showcase PTB capabilities
- Introduce new DeFi primitive
- Increase capital efficiency
- Enable retail participation

This protocol is **native to Sui**.

---

## 🛠️ Tech Stack

- Smart Contract: Move (Sui)
- Execution: Programmable Transaction Blocks
- Frontend: React / Next.js (optional)
- Wallet: Sui Wallet

---

## 📜 License

MIT License

---

## 🤝 Contributors

Built for the Sui ecosystem.
