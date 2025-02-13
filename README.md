# 🚀 Solana SPL Token Launchpad

Welcome to the **Solana SPL Token Launchpad**!  
This is a platform built with **Next.js** to allow easy creation and deployment of **SPL tokens** on the **Solana blockchain**.

Whether you're launching your own project or supporting others, this platform streamlines the token creation process, with simple and intuitive features for developers and non-technical users alike.

---

## 🌟 **Features**
- **🌐 Multi-token Support**: Easily deploy any SPL token on the Solana blockchain.
- **🔑 Wallet Integration**: Connect your wallet (Sollet, Phantom, or any Solana-compatible wallet) for token creation and management.
- **💳 Token Presale Integration**: Conduct token presales directly through the platform.
- **🔒 Security**: All operations are secured with the latest Solana blockchain standards, including wallet authentication and transaction signing.
- **🎨 User-Friendly Interface**: Clean, modern UI built with Next.js and React to help users navigate the process seamlessly.
- **⚙️ Customizable Settings**: Configure your token's name, symbol, total supply, and initial distribution easily.

---

## 🛠️ **Installation**

Follow the steps below to get your Solana SPL Token Launchpad up and running locally:

### 1. Clone the repository
```bash
git clone https://github.com/Immutal0/solana-spl-token-launchpad.git
cd solana-spl-token-launchpad
```

### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables
Create a `.env.local` file in the root of the project and add the following environment variables:

```bash
NEXT_PUBLIC_SOLANA_RPC_URL=https://api.mainnet-beta.solana.com
NEXT_PUBLIC_TWITTER_API_KEY=your_twitter_api_key
NEXT_PUBLIC_TWITTER_API_SECRET=your_twitter_api_secret
SOLANA_PRIVATE_KEY=your_solana_private_key
```

### 4. Run the development server
```bash
npm run dev
```

Visit the application in your browser at `http://localhost:3000`.

---

## 🔄 **How to Use**

1. **Connect your wallet**:  
   Once you open the app, click on the "Connect Wallet" button in the top-right corner. Choose your wallet (Phantom, Sollet, etc.) and authenticate with it.

2. **Create a new SPL token**:  
   After connecting your wallet, you can create a new SPL token. Fill in the details like token name, symbol, total supply, and any other required information. Then, click the "Create Token" button to deploy your token.

3. **Configure token presale**:  
   If you want to conduct a presale for your token, configure the presale settings (price, token cap, duration) and click "Launch Presale". The system will handle the token distribution and track investments.

4. **Manage Tokens**:  
   View your token's details, transfer tokens, and check the current distribution from the "My Tokens" section.

---

## 🧑‍💻 **Tech Stack**
- **Frontend**: Next.js, React, Tailwind CSS
- **Backend**: Solana Web3.js, Node.js
- **Wallet Integration**: Phantom, Sollet
- **Presale Management**: Smart contracts for token distribution
- **Deployment**: Vercel (for production deployment)

---

## ⚙️ **Advanced Features**
- **SPL Token Airdrop**:  
   Allow your users to receive airdrops of your token by configuring the airdrop conditions.

- **Token Vesting**:  
   Set up token vesting schedules for your team, investors, or advisors.

- **Whitelisting for Presale**:  
   Restrict presale access to a selected list of wallet addresses by uploading a whitelist CSV.

---

## 🧪 **Testing**

To test the application locally, you can run the following command:

```bash
npm run test
```

This will run the testing suite, and you can ensure that all features are working correctly before deploying the application to production.

---

## 🚀 **Deployment**

To deploy the app to **Vercel**, follow these steps:

1. Push your code to a GitHub repository.
2. Link the repository to **Vercel** through the Vercel dashboard.
3. Vercel will automatically detect the Next.js app and deploy it.

For more details on deployment, check out the [Vercel Docs](https://vercel.com/docs).

---

## 🤖 **Contributions**

Feel free to fork the project and submit your PRs!  
If you find any bugs or have ideas for new features, open an issue or submit a pull request. I'd love to collaborate!

---

## 👾 **Contact**

For any questions or support, feel free to reach out to me:  
- **Telegram**: [@Immutal0](https://t.me/Immutal0)
- **Twitter**: [@Immutal0_](https://x.com/Immutal0_)

---

## 🔥 **Enjoy building with Solana!**  
Happy token launching and let the blockchain revolution begin! 🌍💥
