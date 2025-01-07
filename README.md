# Omnia.build
Omnia is an intelligent Solana Agent, an on-chain agent powered by Omnia.build that simplifies interactions with the Solana blockchain. Leveraging the Action API, Omnia automates and streamlines various blockchain tasks, enabling seamless and efficient workflows for developers and users alike. 🛠️

---

## Key Features ✨

- **Automated Task Execution**: Perform complex on-chain operations programmatically.
- **Action API Integration**: Connect with external APIs for enhanced functionality.
- **Comprehensive Blockchain Operations**: Manage tokens, interact with smart contracts, send transactions, and more.
- **Modular and Extensible**: Easily configure and extend Omnia for custom use cases.

---

## Use Cases 🔄

Omnia empowers developers and projects with the ability to:

- Automate token transfers, airdrops, and payments.
- Manage and interact with Solana smart contracts seamlessly.
- Monitor on-chain data and generate insightful reports.
- Create tailored workflows for dApps, NFT projects, and DeFi protocols.

---

## Prerequisites 🛠️

To set up and utilize Omnia, ensure you have the following:

- **Node.js** (version 16.x or higher)
- **Solana CLI** (for blockchain interactions)
- **Rust** (for Solana program development and deployment)
- Valid API credentials for the **Action API**

---

## Getting Started ✨

### Installation and Configuration

```bash
# Clone the repository
git clone https://github.com/OmniaBuild/Omnia.git

# Navigate to the project directory
cd Omnia

# Install dependencies
pnpm install

# Create a .env file in the project root with the necessary credentials
echo "ACTION_API_KEY=<your-api-key>" >> .env
echo "SOLANA_RPC_URL=<your-solana-rpc-endpoint>" >> .env

# Ensure your Solana wallet is configured and accessible
solana config set --keypair <path-to-your-wallet-keypair>

# Run predefined tasks using the CLI
pnpm start <task_name> --options

# Example task execution
pnpm start send_transaction --recipient=<address> --amount=<value>

```


## Roadmap 🚩

We aim to build the **most advanced interface** for the Solana Network, enabling users to design AI agents for **autonomous actions and custom strategies**. These agents merge live blockchain data with real-time internet insights, offering an integrated solution for managing the crypto ecosystem.

Our current focus is developing **core infrastructure and agent functionality**.

### Core Infrastructure

- [x] Landing Page
- [x] User Model
- [x] Chat Interface
- [x] Chat Persistence
- [x] Streaming Tool Components
- [x] Embedded Wallet
  - [ ] Migrate to Phantom Embedded Wallet

### Agent Capabilities

- [x] Multi-Tool Usage
- [ ] Multimodal
  - [x] Image
  - [ ] Realtime Voice Conversation
- [ ] Memory Layer
- [ ] Web2 Integration
  - [x] Web Scraping
  - [ ] Twitter Search

### Solana Integration

- [x] SNS (Solana Name Service) Resolver
- [x] Wallet Portfolio
- [ ] Transaction Parser
- [x] NFT Operations
- [x] Basic Token Operations
  - [x] Send/Swap Tokens
  - [x] Token Launch (pump.fun)
- [x] DeFi Integration
  - [x] Jupiter
    - [x] Swaps
    - [x] Price API v2
    - [x] Verified Token Search
    - [ ] Limit Orders
    - [ ] DCA
  - [x] Pump.Fun Integration
    - [x] Deploy Token
  - [x] Dexscreener Integration
    - [x] Token Profile
    - [x] Paid Orders Check
  - [ ] Blinks Integration
  - [x] Magic Eden Integration

### Market Intelligence

- [x] Token Trends (via Defined.fi)
- [x] NFT Trends (via Magic Eden)

### Automation

- [ ] Automated On-Chain Actions
- [ ] Personalized Agent
- [ ] Trading AI

