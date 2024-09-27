# TON OTP Auth

TON OTP Auth is a secure and user-friendly Telegram Mini App designed to manage one-time password (OTP) codes for multiple accounts. It leverages the TON blockchain to encrypt and store OTP entries within a custom NFT owned by the user. This decentralized approach ensures that authentication data remains private and tamper-proof, giving users full control over their security.


## Features

- **Secure OTP Management**: Add and manage OTP codes for multiple accounts in a single app.
- **NFT-Based Storage**: OTP data is encrypted and stored on the TON blockchain within a custom NFT, providing decentralized and tamper-proof data storage.
- **TON Connect 2**: Supports wallets that integrate with the Ton Connect 2 protocol.
- **React-based App**: Built using React and is TWA-ready, providing smooth Telegram Mini App integration.
- **Blockchain Integration**: Fully utilizes the TON blockchain for NFT generation and secure OTP storage.


## Tech Stack

- **React**: Frontend framework for building the Telegram Web App (TWA).
- **Vite**: A modern frontend build tool for faster and leaner development (alternative to Create React App).
- **TON Blockchain**: For NFT generation and decentralized storage of encrypted OTP data.
- **Ton Connect 2**: Integration with wallets supporting the Ton Connect 2 protocol for smooth user interactions.
- **`ton` npm package**: Used for interacting with the TON blockchain.


## How It Works

1. **Set Up**: Users will open the _TON OTP Auth_ app within Telegram.
2. **Add Accounts**: Various accounts (e.g., Google, GitHub) can be added to the app.
3. **NFT Creation**: A custom NFT is generated on the TON blockchain to securely store the encrypted OTP data.
4. **Accessing OTPs**: Users can view and copy their OTP codes directly within the Telegram Mini App.
5. **Security**: All OTP entries are stored in an encrypted format within the NFT, ensuring privacy and security.

## Prerequisites
- [Telegram](https://telegram.org/) installed on your device
- A TON wallet to manage NFTs (e.g. [Tonkeeper](https://tonkeeper.com/))

## Roadmap

- [ ] **MVP Release**: Initial app with basic OTP management and NFT storage.
- [ ] **Ton Connect 2 Integration**: Full support for wallet interactions using Ton Connect 2 protocol.
- [ ] **UI/UX Enhancements**: Improve user experience and add intuitive features for managing multiple OTP accounts.
- [ ] **Additional Features**: Advanced encryption options.


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any bug fixes, feature additions, or enhancements.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add YourFeature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
