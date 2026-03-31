stellar-connect-wallet/
├── public/ # Static assets and PWA manifest
├── src/
│ ├── components/
│ │ ├── freighter.js # Wallet integration utilities
│ │ └── header.js # Main UI component with wallet controls
│ ├── App.js # Root component
│ └── index.js # Application entry point
├── build/ # Production build output
└── package.json # Dependencies and scripts

Install dependencies:

Start the development server:

The app will run on https://localhost:3000 (HTTPS is required for Freighter integration).

Build for production:

💡 Usage
Connecting Your Wallet
Click the "Connect Wallet" button
Approve the connection in the Freighter popup
Your public key and XLM balance will be displayed
Managing Your Address
Copy Address: Click the copy icon next to your truncated address
QR Code: Click the QR icon to generate a shareable QR code
Disconnect: Use the disconnect button to clear wallet data
Future Features (Infrastructure Ready)
Transaction history viewing
Send XLM functionality
Advanced transaction signing
🔧 Configuration
Environment Setup
The app is configured to work with Stellar's testnet by default:

Horizon Server: https://horizon-testnet.stellar.org
Network: Stellar Testnet
HTTPS Requirement
Freighter requires HTTPS for security. The development server is configured with HTTPS=true in the start script.

🧪 Testing
Run the test suite:

Tests are configured using Jest and React Testing Library.

🚀 Deployment
Build the application:

The build folder contains the production-ready files

Deploy to any static hosting service (Netlify, Vercel, GitHub Pages, etc.)

🔒 Security Considerations
All wallet interactions go through Freighter's secure interface
Private keys never leave the user's browser
HTTPS required for all communications
No sensitive data stored locally
🤝 Contributing
Fork the repository
Create a feature branch
Make your changes
Add tests for new functionality
Submit a pull request
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🙏 Acknowledgments
Stellar Development Foundation for the Stellar network
Freighter for the wallet extension
Tailwind CSS for the styling framework
