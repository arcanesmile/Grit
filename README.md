**Grit – Unified Crypto-Fiat Wallet for Africa**
Grit is a localized crypto-fiat wallet that seamlessly converts between stablecoins and local currency instantly, automatically, and safely. It provides a dual interface: a simple mode for everyday users and an advanced mode for crypto‑native users, all powered by the same backend.

**Table of Contents**

Problem & Insight
Solution
Key Features
How It Works
Our Advantage
Market Opportunity
Revenue Model
Future Expansion
Technology Stack
Project Structure
Getting Started
Prerequisites
Backend Setup
Frontend Setup
Environment Variables
API Documentation
Contributing
License
Vision

**Problem & Insight**
**The challenges:**

Frequent P2P disputes and fraud
Fake payment alerts and bank reversals
Frozen accounts and loss of funds
High friction for non‑crypto users
Poor user experience for exchanges and wallets
Yet crypto exchanges struggle to offer direct, reliable off‑ramps into African banks. Non‑crypto users find existing apps too complex and risky. Stablecoins are widely used, but not as everyday money. There is massive adoption potential of USDT, but broken infrastructure hinders ease of use.

**The insight:**
Not all African users want to “trade crypto”. They want to:
Receive money (often in USDT/USDC)
Convert it instantly to local currency
Send it to banks or mobile money
Avoid human negotiation and disputes

**Solution**
Grit is a bridge wallet that:
Instantly swaps USDT / USDC ↔ local currency
Automatically converts funds on wallet entry or exit
Sends local currency directly to mobile money and commercial banks
Requires no P2P interaction – fully automated settlement
To non‑crypto users, it feels like a normal money app; to crypto users and exchanges, it is a powerful off‑ramp and on‑ramp.

 
**Key Features**
Instant Swap Engine – USDT/USDC ⇄ local currency with transparent rates, no negotiation, no middleman.
Direct Bank & Mobile Money Transfers – Withdraw local currency to any supported bank or mobile money account.
No Frozen Accounts – Eliminates risks associated with P2P activity.
Dual UX – Simple mode for everyday users, advanced mode for crypto‑native users (same backend, different frontend experience).
Wallet Compatibility – Exchanges can transfer USDT/USDC directly into Grit, offering users a clean, reliable off‑ramp and reducing support tickets.

**How It Works**
User receives stablecoins (USDT/USDC) into their Grit wallet.
Instant conversion to local currency at a transparent rate.
Withdrawal to bank account or mobile money in local currency.
No counterparty risk – all settlement is automated via smart contracts and traditional banking rails.

 **Our Advantage**
Compared to P2P	Compared to Exchanges	Compared to Banks
No disputes	Better local settlement	Faster
No fraud	Lower operational risk	Borderless
No human delays	Easier regulatory control	Stablecoin‑powered (no sudden deflation)

 **Market Opportunity**
Africa has tens of millions of stablecoin users. Stablecoins are already used for freelancing payments, remittances, and inflation protection, yet off‑ramp infrastructure remains immature.

**Grit positions itself as:**

A consumer app
A B2B settlement layer
A plug‑and‑play off‑ramp for exchanges (via API)

 **Revenue Model**
Swap spread (0.5% – 1%)
Withdrawal fees
FX margins (fixed profit per transaction)
B2B integrations – exchanges and wallets pay for API access

 **Future Expansion**
Cross‑border merchant payouts beyond Africa
Support for additional assets (ETH, BTC, etc.)

**Technology Stack**
Backend
Framework: NestJS
Database: PostgreSQL with Prisma ORM
Authentication: JWT (with refresh tokens)
Caching: Redis
Blockchain: Avalanche (C‑chain) for USDT/USDC smart contract interactions
API Documentation: Swagger

**Frontend**
Framework: React with TypeScript
Build tool: Vite
Styling: Tailwind CSS
Routing: React Router DOM
Icons: React Icons (Material Design icons)
Animations: Framer Motion
HTTP Client: Fetch (custom wrapper)

**NOTE:** THE FRONTEND IS MEANT TO BE BUILT WITH EXPO,REACT WAS USED FOR TESTING.
