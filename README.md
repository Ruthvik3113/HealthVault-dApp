# HealthVault: Medical Report Management and Distribution System (Web3)

HealthVault is a comprehensive Medical Report Management and Distribution System powered by Web3 technologies. This system provides a one-stop solution for hospital management, enabling healthcare institutions to efficiently manage doctor, patient, pathologist, and pharmacist profiles. HealthVault leverages blockchain technology and smart contracts developed in Solidity for the backend, while React.js is used for the frontend. Additionally, the Thirdweb framework is employed to seamlessly integrate the frontend with smart contracts.

## Features

- **Patient Profiles:** Maintain detailed patient records, including personal information, medical history, and prescribed treatments.

- **Doctor Profiles:** Manage doctor profiles, including specialization, qualifications, and appointment schedules.

- **Pathologist Profiles:** Keep a record of pathologists with information about their certifications and the types of tests they can perform.

- **Pharmacist Profiles:** Manage pharmacists' profiles, including their qualifications, licenses, and available medications.

- **Medical Report Management:** Efficiently store and manage medical reports, making them easily accessible to authorized personnel.

- **Smart Contract Integration:** Utilize blockchain and smart contracts for secure and transparent data management.

- **Web3 Integration:** Seamlessly integrate frontend with smart contracts using the Thirdweb framework.

## Getting Started

To get started with HealthVault, follow the steps below:

### Prerequisites

1. Install Node.js: [Download and install Node.js](https://nodejs.org/) if you haven't already.

2. Install Truffle: Truffle is a development environment, testing framework, and asset pipeline for Ethereum. Install it globally by running the following command:

   ```bash
   npm install -g truffle
   ```

3. Install Dependencies: Navigate to the project root directory and install the required Node.js packages:

   ```bash
   npm install
   ```

### Setting up the Development Environment

1. Clone this repository:

   ```bash
   git clone https://github.com/Ruthvik3113/HealthVault-dApp.git
   ```

2. Change into the project directory:

   ```bash
   cd HealthVault
   ```

### Deploy to Goerli Testnet

HealthVault is deployed on the Goerli Testnet Ethereum blockchain. Before deploying, make sure you have configured your Ethereum wallet and set up your Truffle configuration (truffle-config.js) with the necessary network details.

Deploy the smart contracts to the Goerli Testnet by running:

```bash
truffle migrate --network goerli
```

### Running the Application

1. Start the frontend development server:

   ```bash
   npm start
   ```

2. Open your web browser and access the application at [http://localhost:3000](http://localhost:3000).

## Usage

HealthVault offers a user-friendly interface for hospital management. Users can create and manage profiles for doctors, patients, pathologists, and pharmacists. They can also upload, access, and manage medical reports securely.

## Contributing

We welcome contributions from the community. If you want to contribute to HealthVault, please follow our [Contribution Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The HealthVault team acknowledges the open-source community and the developers who have contributed to the various technologies used in this project.

Thank you for choosing HealthVault as your Medical Report Management and Distribution System. We hope it helps streamline healthcare management for your institution. If you encounter any issues or have suggestions for improvement, please feel free to reach out to us.

For any questions or support, contact us at support@healthvault.com.

---

**Note:** This README is a template. Be sure to customize it with specific information about your project, organization, and any additional details you want to provide to users and contributors.
