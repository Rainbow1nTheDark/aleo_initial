# AleoVault: Privacy-Preserved Crypto Wallet
## Discord name - arthas5837

## Introduction
AleoVault is a groundbreaking decentralized application (dApp) on the Aleo platform designed to revolutionize how users manage their cryptocurrency. By leveraging the power of Aleo's zero-knowledge proofs and the simplicity of the Leo programming language, AleoVault offers unparalleled privacy and security for your digital assets. Our mission is to empower users with full control and confidentiality over their transactions and balances.

## Prerequisites
Before you begin with AleoVault, make sure you have the following prerequisites installed:
- **Rust**: Follow the installation guide at [https://www.rust-lang.org/tools/install](https://www.rust-lang.org/tools/install).
- **Aleo SDK**: Get started with Aleo development by visiting [https://developer.aleo.org/testnet/getting_started/developer_toolkit/](https://developer.aleo.org/testnet/getting_started/developer_toolkit/).

## Installation
To get started with AleoVault, clone the repository and set up the project environment:

```shell
git clone https://github.com/AleoVault/aleovault.git
cd aleovault
leo fetch```

## Configuration
Configure your AleoVault environment by creating a .env file in the project root with the following settings:

```NETWORK=testnet
WALLET_PATH=path/to/your/wallet.aleo
```
## Usage
AleoVault simplifies managing your cryptocurrency assets. Here's how to use key features:

### Compiling AleoVault
```leo build```

### Running Tests
``` leo test ```

### Creating a New Wallet
```leo run -- create_wallet```

### Making a Private Transaction
```leo run -- send --from YOUR_WALLET_ADDRESS --to RECIPIENT_WALLET_ADDRESS --amount AMOUNT```

## Contributing
We welcome contributions from the community! Please check our CONTRIBUTING.md for guidelines on how to contribute to AleoVault.

## Support and Community
Join our community on Discord for support, discussions, and updates. Visit our community page to connect: https://aleovault.io/community.

## License
AleoVault is released under the MIT License. See the LICENSE file for more details.

## Acknowledgements
Special thanks to the Aleo team for their incredible support and for providing the tools that made AleoVault possible.

## Additional Resources
- Aleo Documentation: https://developer.aleo.org/
- Leo Language Guide: https://developer.aleo.org/developer/getting_started/leo_overview/
