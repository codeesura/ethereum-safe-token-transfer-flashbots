# Ethereum Safe Token Transfer with Flashbots

This project demonstrates how to perform a safe token transfer between two Ethereum addresses while optimizing transaction fees using the Flashbots Bundle Provider.

## Features

- Transfers tokens between two Ethereum addresses securely.
- Calculates and optimizes gas fees to save on transaction costs.
- Utilizes Flashbots Bundle Provider to include transactions in upcoming blocks.

## Prerequisites

You'll need to have Node.js installed on your machine. You can download it from [here](https://nodejs.org/).

## Dependencies

This project uses the following NPM packages:

- `ethers`: A complete Ethereum wallet implementation and utilities in JavaScript and TypeScript. [GitHub Repository](https://github.com/ethers-io/ethers.js/)
- `@flashbots/ethers-provider-bundle`: Flashbots library for Ethers.js. [GitHub Repository](https://github.com/flashbots/ethers-provider-flashbots-bundle)

## Installation

1. Clone this repository:

```bash
git clone https://github.com/codeesura/ethereum-safe-token-transfer-flashbots.git
```

2. Change to the project directory:

```bash
cd ethereum-safe-token-transfer-flashbots
```

3. Install the required dependencies:

```bash
npm install
```

## Configuration

1. Replace `YOUR_API_KEY` with your Alchemy API key in the `provider` constant.
2. Replace `PRIVATE_KEY` and `HACK_PRIVATE_KEY` with the private keys of the Ethereum addresses you want to transfer tokens between.

## Usage

1. To start the token transfer, run the following command:

```bash
node app.js
```

2. The script will listen for new blocks and attempt to include the token transfer in the upcoming block. Once the transaction is included, you'll see a confirmation message in the console.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [Issues](https://github.com/codeesura/ethereum-safe-token-transfer-flashbots/issues) page.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/codeesura/ethereum-safe-token-transfer-flashbots/blob/main/LICENSE) file for more details.
