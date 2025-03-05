# Ethereum-Flash-tool
Ethereum Flasher - is a standalone Windows application designed for educational purposes to simplify sending flash token transactions (USDT, USDC, DAI) on the Ethereum blockchain.
Built with Python, tkinter, and web3.py, this tool is packaged as an .exe file for easy use without requiring a Python environment.

Key Features:

- Portable Executable: No installation or Python setup needed—just download and run the .exe.
- User-Friendly Interface: Clean GUI for entering wallet private keys, recipient addresses, and transaction details.
- Supported Tokens: Send USDT, USDC, and DAI with automatic decimal handling.
- Transaction Management: Send transactions and cancel pending ones by overriding with a higher gas price.
- Real-Time Feedback: Displays wallet address, ETH balance, and transaction status.
- Infura Integration: Connects to the Ethereum mainnet using a customizable Infura ID.
- Safety Features: Validates Ethereum addresses and warns about insufficient gas funds.

Prerequisites:

- A Windows operating system (tested on Windows 10/11)
- An Infura account and API key for Ethereum mainnet access
- An Ethereum wallet with a private key and some ETH for gas fees

How to Use:

Download the latest release (EthereumFlasher.exe) from the Releases section.
Run the .exe file.
Input your Infura ID, private key, and transaction details to send flash tokens.
Source Code:

Disclaimer:

This tool is intended solely for educational and testing purposes. Use it responsibly and ensure you have sufficient ETH to cover gas fees. The developer is not liable for any loss of funds due to misuse or errors.

Contributions:

Feel free to fork, submit issues, or suggest improvements! Contributions to enhance security, add features, or optimize the executable are welcome.

This version emphasizes the .exe format, provides instructions for end-users, and still includes the source code context for developers.
