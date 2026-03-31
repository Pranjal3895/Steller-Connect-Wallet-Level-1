🌟 Stellar Connect Wallet

A modern React-based web application that enables users to securely connect and interact with their Stellar wallet using the Freighter extension.

📁 Project Structure
stellar-connect-wallet/
├── public/              # Static assets and PWA manifest
├── src/
│   ├── components/
│   │   ├── freighter.js  # Wallet integration utilities
│   │   └── header.js     # UI component with wallet controls
│   ├── App.js            # Root component
│   └── index.js          # Entry point
├── build/               # Production build output
└── package.json         # Dependencies and scripts
⚙️ Installation & Setup
1. Install Dependencies
npm install
2. Start Development Server
npm start

The application will run at:

https://localhost:3000

⚠️ Note: HTTPS is required for Freighter wallet integration.

🏗️ Build for Production
npm run build

This will generate optimized production files in the build/ directory.

💡 Features & Usage
🔗 Connect Your Wallet
Click on "Connect Wallet"
Approve the connection in the Freighter popup
View your public key and XLM balance
📋 Manage Wallet Address
Copy Address: Click the copy icon
QR Code: Generate a shareable QR code
Disconnect: Safely disconnect your wallet
🚧 Upcoming Features
📜 Transaction history
💸 Send XLM functionality
✍️ Advanced transaction signing
🔧 Configuration
🌐 Network Setup

The app is configured for Stellar Testnet:

Horizon Server: https://horizon-testnet.stellar.org
Network: Stellar Testnet
🔐 HTTPS Requirement

Freighter requires a secure connection. Ensure your environment uses HTTPS:

HTTPS=true npm start
🧪 Testing

Run the test suite:

npm test
Built with Jest and React Testing Library
🚀 Deployment
Steps:

Build the project:

npm run build
Deploy the build/ folder to any static hosting service:
Netlify
Vercel
GitHub Pages
🔒 Security Considerations
All wallet interactions are handled via Freighter
Private keys never leave the user's browser
HTTPS is mandatory for secure communication
No sensitive data is stored locally
🤝 Contributing

Contributions are welcome!

Steps:
Fork the repository
Create a feature branch
Make your changes
Add tests (if applicable)
Submit a pull request
📄 License

This project is licensed under the MIT License.
See the LICENSE file for more details.

🙏 Acknowledgments
Stellar Development Foundation – Stellar Network
Freighter – Wallet Extension
Tailwind CSS – Styling Framework

<img width="3200" height="1904" alt="Screenshot 2026-04-01 011640" src="https://github.com/user-attachments/assets/31d06fec-e476-4585-8048-0660826d3ea8" />

<img width="3200" height="1904" alt="Screenshot 2026-04-01 011321" src="https://github.com/user-attachments/assets/10125a50-33df-4f5a-ac7a-1240b3d00582" />
