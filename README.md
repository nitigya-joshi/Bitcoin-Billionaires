# CrowdVault

## Table of Contents

- [Deployed site](#the-link-to-the-deployed-project)
- [The problem CrowdVault solves](#the-problem-crowdvault-solves)
- [Challenges we ran into](#challenges-we-ran-into)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Deployed Site

Check out the deployed version of CrowdVault [here](https://crowdvault.netlify.app/).

## The problem CrowdVault solves

The CrowdVault crowdfunding app based on Web3 addresses several key challenges faced by traditional crowdfunding platforms:

1. Centralization and Intermediaries: Traditional crowdfunding platforms often rely on centralized intermediaries, which can introduce inefficiencies, restrictions, and potential trust issues. CrowdVault eliminates the need for intermediaries by leveraging the decentralized nature of Web3 technology, providing a direct connection between project creators and backers.

2. Lack of Transparency: Transparency is a significant concern in crowdfunding, as backers want assurance that their contributions are being used appropriately. With CrowdVault built on Web3, all transactions and project details are recorded on the blockchain, ensuring transparency and traceability throughout the crowdfunding process.

3. Payment and Currency Limitations: Traditional platforms usually have limited payment options and may be restricted to specific currencies. CrowdVault, powered by Web3, opens up a broader range of payment possibilities, including cryptocurrencies, enabling backers from around the world to participate without currency barriers.

4. Data Security and Privacy: Centralized platforms may collect and store sensitive user data, posing potential security and privacy risks. In contrast, CrowdVault's decentralized architecture leverages the Filecoin network for data storage, ensuring enhanced security, privacy, and control over personal information.

5. Access and Inclusivity: Traditional crowdfunding platforms may have geographic restrictions or stringent project approval processes, limiting access and inclusivity. CrowdVault, as a Web3 application, operates in a decentralized manner, making it accessible to anyone with internet connectivity and fostering global participation and diversity.

By addressing these challenges, CrowdVault provides a more efficient, transparent, and inclusive crowdfunding experience.

## Challenges we ran into

During the development of CrowdVault, we encountered various challenges and hurdles. One notable issue was related to integrating the Web3 functionality into our application.

At first, we faced difficulties in establishing a connection with the Filecoin Testnet and interacting with smart contracts. We encountered compatibility issues between different versions of Web3 libraries and had trouble retrieving data from the blockchain.

To overcome this hurdle, we conducted thorough research and sought assistance from the developer community. We extensively reviewed the Web3 documentation and explored community forums to gain insights from others who had encountered similar issues.

Through experimentation and trial and error, we identified the specific version of the Web3 library that was compatible with our project requirements. We also implemented proper error handling and debugging techniques to pinpoint and resolve any issues that arose during the integration process.

Additionally, we engaged with the Web3 community through online forums and chat groups. We sought advice from experienced developers and received valuable guidance on best practices and potential workarounds for our specific challenges.

By combining our own problem-solving efforts, utilizing available resources, and seeking support from the developer community, we successfully overcame the hurdles associated with integrating Web3 functionality into CrowdVault. This allowed us to create a robust and functional crowdfunding application that leverages the power of the Filecoin Testnet and provides an exceptional user experience.

## Installation

1. Clone the repository.
2. Install the dependencies using `npm install`.

## Usage

To run the CrowdVault project, use the following command:

```
npm start
```
The project will start running, and you can access it in your browser at http://localhost:3000.

## Contributing

We welcome contributions to the CrowdVault project! If you'd like to contribute, please follow the steps below:

1. Fork the repository on GitHub.
2. Create a new branch for your feature or bug fix:
```
git checkout -b feature/your-feature-name
```
or
```
git checkout -b bugfix/your-bug-name
 ```
3. Make your modifications and additions to the codebase.
4. Test your changes thoroughly.
5. Commit your changes with descriptive commit messages:
```
git commit -m "Add feature: your feature name"
```
6. Push your branch to your forked repository:
```
git push origin feature/your-feature-name
```
7. Open a pull request on the original repository. Provide a clear description of your changes and their purpose.
8. We will review your pull request and provide feedback as needed. Once approved, your changes will be merged into the main branch.

Thank you for considering contributing to CrowdVault! Together, we can create a powerful and inclusive crowdfunding platform.
