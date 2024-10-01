# NFT Market Place

A decentralized marketplace for NFTs built with Solidity and Hardhat.

## Getting Started

Follow these steps to set up and run the project locally.

### 1. Clone the Repository

In your terminal, run the following command to clone the repository:

```bash
git clone https://github.com/pixyglee/nftmarket.git
```

### 2. Install Dependencies

Navigate to the root folder of the cloned repository, and install the required dependencies by running:

```bash
npm install
```

### 3. Compile, Test, and Deploy Smart Contracts

#### Compile the contracts:

```bash
npx hardhat compile
```

#### Run the tests:

```bash
npx hardhat test
```

#### Start a local Hardhat node:

```bash
npx hardhat node
```

#### In a new terminal window, deploy the smart contracts:

```bash
npx hardhat run scripts/deploy.js --network localhost
```

### 4. Start the Frontend

In another terminal, start the development server:

```bash
npm run dev
```

