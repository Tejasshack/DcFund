
# DcFund

**DcFund** is a decentralized crowdfunding platform that leverages blockchain technology to enable transparent and secure fundraising for projects. Built using modern web technologies and decentralized protocols, it empowers users to contribute directly to projects without intermediaries, ensuring transparency and reducing fees.

## Key Features

- **Decentralized Platform**: Built on the Ethereum blockchain, ensuring transparency, security, and trust through smart contracts.
- **Smart Contracts**: Written in Solidity and deployed using Hardhat to handle the crowdfunding process, including fund collection and withdrawal, in a trustless environment.
- **Project Creation**: Users can create projects, set funding goals, and provide details about their project, such as descriptions, timelines, and rewards for backers.
- **Contribution Tracking**: Real-time tracking of contributions, allowing users to monitor project progress and see how funds are utilized.
- **Secure Transactions**: Contributions are handled securely via blockchain, with funds only released when specific conditions, like funding goals, are met.

## Technologies Used

- **Next.js**: For building a fast and scalable web application with server-side rendering capabilities.
- **TypeScript**: To add static type checking and enhance code reliability.
- **Hardhat**: A development environment for compiling, deploying, testing, and debugging Ethereum smart contracts.
- **Solidity**: For writing smart contracts that manage the decentralized crowdfunding process.
- **Tailwind CSS**: To design a responsive and modern UI with utility-first styling.
- **Netlify**: To deploy and host the frontend application with CI/CD integrations for faster development cycles.

## Screen Shots
![image](https://github.com/user-attachments/assets/5291fd21-bb71-4279-83f9-fe5fd6915f8d)

## Campaigns
![image](https://github.com/user-attachments/assets/44221123-10b1-4267-a04b-7778e28d82ca)



## Project Structure

- `contracts/`: Contains the Solidity smart contracts that define the logic for the crowdfunding platform.
- `pages/`: The Next.js pages that handle routing and rendering of the front end.
- `components/`: Reusable UI components built with Tailwind CSS.
- `scripts/`: Scripts for deploying and interacting with the smart contracts using Hardhat.
- `types/`: TypeScript interfaces and types for better code maintainability.

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- MetaMask or any Ethereum wallet
- Hardhat
- Solidity

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/DcFund.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd DcFund
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Compile Smart Contracts**:
   ```bash
   npx hardhat compile
   ```

5. **Deploy Contracts**:
   ```bash
   npx hardhat run scripts/deploy.js --network <network>
   ```

6. **Start Development Server**:
   ```bash
   npm run dev
   ```

## Usage

1. **Create Projects**: Users can create a new crowdfunding campaign by providing details like a project description, funding goal, and deadline.
2. **Contribute to Projects**: Contributors can explore various projects and support them by sending Ether.
3. **Track Progress**: Users can track the project's funding status in real-time.
4. **Withdrawal**: Once the goal is achieved, project creators can withdraw the funds.

## Roadmap

- **Integration with IPFS**: For decentralized storage of project data.
- **Token Rewards**: Implement tokenized rewards for backers.
- **Mobile Support**: Improve mobile responsiveness.
- **Multichain Support**: Enable crowdfunding on multiple blockchain networks.

## Contributing

Contributions are welcome! Please create a pull request or open an issue if you'd like to contribute or report any problems.

## License

This project is licensed under the MIT License.
