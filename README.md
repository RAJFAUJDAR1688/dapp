# dapp

### Overview

Welcome to "My First dApp," a simple decentralized application (dApp) built with basic HTML, CSS, and Ethereum blockchain technology. This dApp allows users to set and retrieve their mood, demonstrating the integration of a smart contract written in Solidity with a basic web interface using Ether.js.

### Features

- **Set Mood**: Users can input their current mood and set it within the dApp.
- **Get Mood**: Users can retrieve their previously set mood.

### Prerequisites

To interact with this dApp, you need:
- An Ethereum-enabled browser with MetaMask extension installed.
- Access to an Ethereum test network (e.g., Goerli).
- Basic understanding of Ethereum blockchain technology.

### Instructions

1. **Clone Repository**: Clone this repository to your local machine.

2. **Set up Remix IDE**: Use Remix IDE or any other Solidity development environment to deploy the provided smart contract (`MoodContract.sol`) to your chosen Ethereum test network.

3. **Configure MetaMask**:
   - Ensure your MetaMask extension is connected to the same Ethereum test network.
   - Import the account you used to deploy the smart contract into MetaMask.

4. **Update Contract Address and ABI**:
   - Update the `MoodContractAddress` variable in the HTML file with the deployed smart contract address.
   - Ensure the `MoodContractABI` variable matches the ABI of your deployed smart contract.

5. **Launch dApp**:
   - Open the `index.html` file in your preferred web browser.

6. **Interact with the dApp**:
   - Use the input field to set your mood and click "Set Mood" button.
   - Click the "Get Mood" button to retrieve your previously set mood.

### Known Issues

- As of the current version, there are no known issues. Please report any encountered issues to the repository's issue tracker.

### Contributing

Contributions are welcome! Feel free to submit pull requests, bug reports, feature requests, or suggestions via the repository's issue tracker.

### License

This project is licensed under the [MIT License](LICENSE).

---

Thank you for using "My First dApp"! If you have any questions or feedback, please don't hesitate to reach out.
