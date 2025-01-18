# Klassi

Klassi is a decentralized platform that allows users to pay for Solana transaction fees by watching ads. Advertisers stake SOL to showcase their ads, and the gas fees for users' transactions are sponsored using this staked SOL. This project leverages the T3 stack for a modern and scalable solution.

## Features

### For Users
- Submit Solana draft transactions (base64 string or URL).
- Watch 2 ads (60 seconds each) with anti-tab-switch and completion tracking mechanisms.
- Get gas fees sponsored by ad providers for seamless Solana transactions.

### For Advertisers
- Create and manage ad accounts via a dedicated dashboard.
- Stake SOL to increase ad visibility and ranking.
- Create ad sets (videos with metadata like duration).
- Track staking balances and ad performance.

---

## Installation

### Prerequisites
- **Node.js**: Install the latest version.
- **pnpm**: Install via `npm install -g pnpm`.
- **Solana CLI**: Set up the Solana development environment ([guide](https://docs.solana.com/cli/install-solana-cli-tools)).

### Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/klassi.git
   cd klassi
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```env
     DATABASE_URL="postgresql://<username>:<password>@<host>:<port>/<database>"
     NEXTAUTH_SECRET="<your-nextauth-secret>"
     NEXTAUTH_URL="http://localhost:3000"
     ```

4. Run the development server:
   ```bash
   pnpm dev
   ```

5. Start the Solana program (Devnet):
   - Deploy your Anchor program by following the [Anchor deployment guide](https://book.anchor-lang.com/).

---

## Contributing

We welcome contributions from the community! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Submit a pull request with a detailed description.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

- Built with love using the T3 stack.
- Powered by Solana's high-performance blockchain.

---

## Contact

For questions or feedback, reach out to [hashmad.xyz@gmail.com](mailto:hashmad.xyz@gmail.com).
