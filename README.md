ICP Token Wallet
Overview
This project is a Rust-based token wallet for the Internet Computer Protocol (ICP) blockchain. It supports basic functionalities such as sending and receiving IRCRC2 tokens, and includes basic wallet security features. The project demonstrates proficiency with Rust and blockchain principles.

Features
Send Tokens: Ability to send IRCRC2 tokens to other addresses.
Receive Tokens: Capability to receive tokens and update the balance.
Balance Display: Show the current token balance of the wallet.
Basic Security: Implemented security measures to protect wallet transactions.
Requirements
Rust programming language
DFX (Dfinity's SDK for ICP)
Basic understanding of token standards (IRCRC2) and blockchain security practices
Setup
Prerequisites
Install Rust: Rust Installation Guide
Install DFX: DFX Installation Guide
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/NiteshAnand190/icp_wallet.git
Navigate to the project directory:

bash
Copy code
cd icp_wallet
Install dependencies:

bash
Copy code
cargo build
Start the local ICP network:

bash
Copy code
dfx start --background
Deploy the canisters:

bash
Copy code
dfx deploy
Testing
Run unit tests:

bash
Copy code
cargo test
Verify canister status:

bash
Copy code
dfx canister status icp_wallet_backend
Usage
Interact with the backend canister:

You can interact with the canister via the Candid interface URL provided after deployment.

Contributing
Feel free to contribute to this project by submitting issues or pull requests. For detailed contribution guidelines, please refer to the CONTRIBUTING.md file.
