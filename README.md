NFT Marketplace Full Stack Project Welcome to the NFT Marketplace repository! This project is a comprehensive, full-stack NFT marketplace built using modern web technologies and blockchain. It leverages React for the front end, Solidity for writing smart contracts, MetaMask for handling blockchain interactions, and Hardhat for smart contract development and testing. This project demonstrates the integration of decentralized applications (dApps) with blockchain technology to create a functional and interactive NFT marketplace.

Features User Authentication: Users can connect their MetaMask wallet to authenticate and interact with the marketplace. NFT Minting: Users can mint their own NFTs directly on the platform. NFT Listing: Minted NFTs can be listed for sale on the marketplace. NFT Purchasing: Users can browse listed NFTs and make purchases securely. Transaction History: View the history of transactions made on the platform. Smart Contract Interaction: Fully functional interaction with Ethereum blockchain smart contracts. Responsive Design: Fully responsive design for seamless user experience across devices. Technologies Used Frontend:

React.js Redux (for state management) Web3.js (for blockchain interaction) Tailwind CSS (for styling) Backend:

Node.js Express.js Blockchain:

Solidity (smart contract development) Hardhat (development and testing framework) MetaMask (Ethereum wallet and blockchain interaction) Getting Started Follow these steps to get the project up and running on your local machine:

Prerequisites Node.js and npm MetaMask extension installed in your browser An Ethereum testnet account (e.g., Ropsten, Rinkeby) Installation Clone the repository:

bash git clone https://github.com/yourusername/nft-marketplace.git cd nft-marketplace Install dependencies:

bash npm install Compile the smart contracts:

bash npx hardhat compile Deploy the smart contracts:

bash npx hardhat run scripts/deploy.js --network your-network Start the frontend development server:

bash npm start Project Structure contracts/: Contains the Solidity smart contracts. scripts/: Scripts for deploying the smart contracts. src/: React frontend source code. src/components/: React components. src/redux/: Redux store and slices. src/utils/: Utility functions and helpers. public/: Public assets and static files. Contributing Contributions are welcome! Please follow these steps to contribute:

Fork the repository. Create a new branch: git checkout -b feature/your-feature-name. Make your changes and commit them: git commit -m 'Add some feature'. Push to the branch: git push origin feature/your-feature-name. Submit a pull request. License This project is licensed under the MIT License - see the LICENSE file for details.

Contact For any questions or feedback, please open an issue or contact me at abhishekmahajan8285@gmail.com.

Happy coding! 🚀
