# ERC20 Token Project

This project is a simple implementation of an ERC-20 token using Truffle and Ganache CLI. It includes all necessary files to deploy and test the token on a local blockchain.

## Project Structure

```
erc20-token-project
├── contracts
│   ├── ERC20Token.sol        # Solidity code for the ERC-20 token contract
│   └── Migrations.sol        # Migration contract for Truffle
├── migrations
│   ├── 1_initial_migration.js # Deploys the Migrations contract
│   └── 2_deploy_contracts.js  # Deploys the ERC20Token contract
├── test
│   └── ERC20Token.test.js     # Test cases for the ERC20Token contract
├── truffle-config.js          # Truffle configuration file
├── package.json                # npm configuration file
└── README.md                   # Project documentation
```

## Getting Started

### Prerequisites

- Node.js (version 12 or higher)
- npm (Node package manager)
- Truffle (install globally using `npm install -g truffle`)
- Ganache CLI (install globally using `npm install -g ganache-cli`)

### Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd erc20-token-project
   ```

2. Install the dependencies:
   ```
   npm install
   ```

### Running Ganache

Start Ganache CLI in a separate terminal:
```
ganache-cli
```

### Deploying the Contract

1. Open a new terminal and navigate to the project directory.
2. Run the migration to deploy the contracts:
   ```
   truffle migrate
   ```

### Running Tests

To run the test cases for the ERC20Token contract, execute:
```
truffle test
```

## License

This project is licensed under the MIT License. See the LICENSE file for details.