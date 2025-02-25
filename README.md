# 🏆 Monad Lottery Game 🎲  

A simple **lottery game** built on the **Monad Testnet**, where players can enter by sending testnet **$MON**, and a winner is randomly selected when the lottery ends.  

## 📌 Features  
✅ Players can enter by sending **0.01 $MON** or more  
✅ The lottery **automatically selects a random winner**  
✅ Only the **contract owner can start and end** the lottery  
✅ Built using **Solidity & Hardhat** for smart contract development  
✅ Ready for **deployment on Monad Testnet**  

## 🛠 Tech Stack  
- **Solidity** (Smart Contract)  
- **Hardhat** (Development & Testing)  
- **Ethers.js** (Blockchain Interaction)  
- **React.js** (Frontend, upcoming)  

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  
```sh  
git clone https://github.com/YOUR_GITHUB_USERNAME/MonadLotteryGame.git  
cd MonadLotteryGame  
```

### 2️⃣ Install Dependencies  
```sh  
npm install  
```

### 3️⃣ Configure Environment Variables  
Create a `.env` file in the root directory:  
```  
MONAD_RPC_URL="https://testnet-rpc.monad.xyz"  
PRIVATE_KEY="YOUR_WALLET_PRIVATE_KEY"  
```

### 4️⃣ Deploy to Monad Testnet  
```sh  
npx hardhat run scripts/deploy.js --network monadTestnet  
```

### 5️⃣ Run the Frontend (Coming Soon)  
```sh  
cd frontend  
npm install  
npm run dev  
```

## 📜 Smart Contract  
The core contract is written in **Solidity** and deployed on **Monad Testnet**.  

## 🎯 Roadmap  
- [x] Deploy on Monad Testnet  
- [ ] Build Frontend with React  
- [ ] Add WalletConnect & UI Enhancements  
- [ ] Improve Security & Code Audits  

## 📢 Contributing  
Feel free to **fork, modify, and contribute**! Pull requests are welcome.
