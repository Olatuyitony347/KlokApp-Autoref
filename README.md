# Klok.ai Auto Referrals and Chat Bot

The Klok.ai Auto Chat Bot is designed to automate the creation of multiple accounts, each with a unique wallet, and generate diverse, randomized chat interactions with the Klok.ai platform.

## Register

Here: https://klokapp.ai/app

## Features
- **Wallet Generation**: Creates unique Ethereum wallets using `eth-account`.
- **Authentication Flow**: Authenticates wallets using a nonce and signed message.
- **Chat Generation**: Loads over 5000+(you can add more if you want or change it) diverse chat questions from `chats.txt` and generates 3-5 random chats per session.
- **Proxy Handling**: Supports one account per proxy with automatic proxy rotation.
- **Error Handling**: Implements robust retry mechanisms for network errors and rate limits.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/kelliark/KlokApp-Autoref
   ```
2. Navigate to the project directory:
   ```bash
   cd KlokApp-Autoref
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the script:
   ```bash
   python main.py
   ```
2. Follow the on-screen instructions to generate accounts and start chat sequences.

## Configuration
- **Proxies**: Add your proxies to the `proxies.txt` file.
- **Referral Codes**: Add your referral codes to the `refs.txt` file.

## Contributing
Feel free to submit issues or pull requests. Contributions are welcome!

## License
This project is licensed under the MIT License.

## Notes
Use at your own risk, all risk are borne with user.
