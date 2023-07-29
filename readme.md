# Celo Uganda Developer Workshop 3.0

## ⚡ DELIGHT ⚡

### PROJECT READ ME FORMAT

 Project Description
  Delight is an innovative e-commerce platform that harnesses the power of the Celo blockchain to transform online shopping. With a focus on security, transparency, and efficiency, Delight offers a decentralized shopping experience that benefits both buyers and sellers.
 Powered by Celo's cutting-edge blockchain technology, Delight ensures secure and transparent payment pocessing for all transactions. By leveraging the low transaction fees and fast settlement times of the Celo network, the platform minimizes costs and accelerates order processing, providing a seamless shopping experience for users.
 To foster a trustworthy and reliable ecosystem, Delight incorporates identity and reviews verification through decentralized systems. Sellers' identities are verified, and product reviews are authenticated, promoting a community built on trust and confidence.
 Smart contracts play a vital role in automating various processes, such as order fulfillment and dispute resolution, enhancing the overall efficiency of the platform.
 Delight's user-friendly and responsive design ensures a seamless shopping experience across devices, making it accessible to customers on desktops, tablets, and mobile phones.
 For merchants, Delight offers convenient inventory management tools, enabling them to efficiently manage their product listings and track sales.
 Customers benefit from real-time order tracking, keeping them informed about the status of their purchases from checkout to delivery.
 Whether you are a buyer looking for a secure and convenient shopping experience or a seller seeking a reliable and efficient platform to reach a broader audience, Delight is your one-stop destination.
Join us on Delight, the Celo-powered e-commerce platform that redefines the way we shop online - empowering businesses and delighting customers worldwide.

Functionalities
User Authentication and Account Management: Users can create accounts, log in, and manage their profiles. Sellers and buyers have distinct roles, each with relevant permissions and access.

Product Listing and Management: Sellers can list their products with detailed descriptions, images, and prices. They can also manage their inventory, update product information, and mark items as available or sold out.

Secure Payments with Celo: Delight integrates with the Celo blockchain for secure and transparent payment processing. Buyers can make purchases using their Celo wallets, and sellers receive payments directly.

Decentralized Identity Verification: To promote trust within the community, sellers' identities are verified through decentralized identity systems, adding an extra layer of security to the platform.

Product Reviews and Ratings: Customers can leave reviews and ratings for products they've purchased. These reviews help build a reputation for sellers and assist other buyers in making informed decisions.

Real-Time Order Tracking: Buyers can track the status of their orders in real-time, from payment confirmation to shipment and delivery updates.

Smart Contract Automation: Smart contracts are employed to automate various processes, such as order fulfillment and dispute resolution, reducing manual intervention and ensuring efficiency.

Low Transaction Fees: Delight leverages the Celo blockchain's cost-efficient nature, resulting in minimal transaction fees for both buyers and sellers.

Responsive User Interface: Delight's user interface is responsive and adaptable to various devices, providing an optimal shopping experience on desktops, tablets, and mobile phones.

Search and Filter Functionality: Buyers can easily search for products using keywords and apply filters to narrow down their choices based on price, category, or seller rating.

By incorporating these functionalities, Delight aims to create a reliable, efficient, and delightful e-commerce experience for all users while harnessing the benefits of Celo blockchain technology.
Installation
Follow these steps to install and configure Delight:

Clone the repository: git clone https://github.com/kaksv/delight.git

Install dependencies: cd delight && npm install

Configure the Celo network: Update the network configuration in config.js to connect to the Celo blockchain.

For a comprehensive list of resources and information, review [Celo Docs.](https://docs.celo.org/)

### QUICK START GUIDES

View the [Developer Code Examples page](https://docs.celo.org/developer#quickstart) to get started using the Celo SDKs with guided coding exercises.

### Tutorials
- [Tutorial - Celo Developer Blog](https://docs.celo.org/blog)

### TOOLS

#### Boilerplates
- [celo-composer](https://github.com/celo-org/celo-composer#celo-composer)
	- Celo Composer allows you to quickly build, deploy, and iterate on decentralized applications using Celo. It provides a number of frameworks, examples, and Celo specific functionality to help you get started with your next dApp.

#### SDKs

-   [ContractKit](https://docs.celo.org/developer/contractkit#what-is-contractkit)
	-   Javascript package of Celo blockchain utilities
	-   Manage connections to the Celo blockchain, accounts, send transactions, interact with smart contracts, etc.
	-   A set of wrappers around the core protocol smart contracts to easily connect with contracts related to governance, validators, on-chain exchange, etc.
	-   Includes [web3.js](https://web3js.readthedocs.io/en/v1.2.4/)
-   [Celo Ethers.js Wrapper](https://github.com/celo-tools/celo-ethers-wrapper) (experimental)
	-   A minimal wrapper to make [ethers.js](https://docs.ethers.io/v5/) compatible with the Celo network
-   [use-react](https://github.com/celo-org/react-celo)
	- The easiest way to access Celo in your React applications 🔥. react-celo is a React hook for managing access to Celo with a built-in headless modal system for connecting to your users wallet of choice.
	- Now your DApp can be made available to everyone in the Celo ecosystem, from Valora users to self custodied Ledger users.
	- By default react-celo is styled so that you can drop it into your application and go, however it's fully customisable so you can maintain a consistent UX throughout your application.
-   [DappKit](https://docs.celo.org/developer-guide/dappkit)
	-   Easily connect to the [Valora](http://valoraapp.com/) wallet with your React Native mobile application
	-   Valora manages user account, private keys and transaction signing, so you can focus on building your dapp
	-   Learn more and see the code with the [Dappkit truffle box](https://github.com/critesjosh/celo-dappkit)
-   [Python SDK](https://github.com/blaize-tech/celo-sdk-py)
-   [Java SDK](https://github.com/blaize-tech/celo-sdk-java)
	- [Android with Java SDK](https://github.com/bcamacho/celo-android-java-sdk-test-example)
- [iOS SDK](https://github.com/heymateag/celoiossdk)



#### Infrastructure

-   [Valora](https://valoraapp.com/) provides a clean, intuitive UI where users can send transactions and interact with smart contracts
-   [Forno](https://stackedit.io/developer-guide/forno)
-   Node access service so you can connect your dapp to the Celo blockchain without having to run node infrastructure
-   [ODIS](https://stackedit.io/developer-resources/contractkit/odis.md)
-   Oblivious decentralized identity service
-   Lightweight identity layer that makes it easy to send cryptocurrency to a phone number
-   Blockscout block explorers
-   [Alfajores testnet](http://alfajores-blockscout.celo-testnet.org/) & [mainnet](http://explorer.celo.org/)
-   [Stats.celo.org](http://stats.celo.org/) to check network activity and health


#### Networks

-   [Alfajores Testnet](https://docs.celo.org/getting-started/alfajores-testnet)
-   [Faucet](https://celo.org/developers/faucet) for free testnet CELO and cUSD
-   [Forno](https://docs.celo.org/developer-guide/forno) supports connections to alfajores
-   Requires Alfajores Celo wallet for mobile device testing (please request, support@clabs.co)
-   [Baklava testnet](https://docs.celo.org/getting-started/baklava-testnet) for validators and testing protocol changes


#### Ethereum Tools

-   Similarities between Celo and Ethereum means you can use many of the most popular Ethereum developer tools.
-   Celo supports the EVM, so tools for writing smart contracts in Solidity (or any language that compiles to EVM bytecode) are compatible with Celo
-   ERC20, NFT (ERC721) and other smart contract interface standards are supported, see [Celo for Ethereum Developers](https://docs.celo.org/developer-guide/celo-for-eth-devs)
- [Truffle](https://www.trufflesuite.com/)
- [OpenZeppelin](https://openzeppelin.com/)
- [Remix](https://remix.ethereum.org/)

#### Ongoing projects

-   [Community projects](https://docs.celo.org/developer-guide/celo-dapp-gallery)
-   [Grant recipients](https://celo.org/experience/grants/directory)

#### Web wallets
  -  [celowallet.app](https://celowallet.app/)
  -  [Celo Terminal](https://github.com/zviadm/celoterminal/)


#### Community

-   Join our [Discord](https://chat.celo.org/)
-   [Discourse Forum](https://forum.celo.org/)



License
This repository includes an unlicensed statement though you may want to choose a different license.
