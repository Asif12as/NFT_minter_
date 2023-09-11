# NFT_minter_

# NFT Minter Website

Welcome to the NFT Minter Website repository! This project is a web application built using React-Vite, Express.js, Multer, CORS, Node.js, HTML, CSS, JavaScript, and it integrates with the Stardust service for smart contract development and API keys.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Configuration](#configuration)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to provide a user-friendly interface for minting Non-Fungible Tokens (NFTs) by leveraging blockchain technology. It uses React-Vite for the front-end, Express.js for the back-end, and Stardust for smart contract interactions. With this NFT Minter, users can easily create and manage their own unique NFTs.

## Features

- **User-friendly Interface**: The web application offers an intuitive interface for users to mint NFTs without technical expertise.
- **File Upload**: Users can upload their image or media files to be associated with the NFT.
- **Custom Metadata**: Users can add custom metadata and attributes to their NFTs.
- **Stardust Integration**: Smart contracts for NFTs are deployed and managed using the Stardust service.
- **Security**: The application includes CORS handling and Multer for secure file uploads.
- **Responsive Design**: The website is designed to work seamlessly on various devices and screen sizes.

## Getting Started

To get started with the NFT Minter Website, follow these steps:

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/your-username/nft-minter.git
   ```

2. Install the required dependencies for both the front-end and back-end:

   ```
   cd nft-minter/client
   npm install

   cd ../server
   npm install
   ```

3. Configure the application (see [Configuration](#configuration) section).

4. Start the development servers for both the client and server:

   ```
   # Start the front-end development server
   cd ../client
   npm run dev

   # Start the back-end development server
   cd ../server
   npm run dev
   ```

5. Open your browser and access the website at `http://localhost:3000`.

## Project Structure

The project is structured as follows:

- `client/`: Front-end codebase using React-Vite.
- `server/`: Back-end codebase using Express.js.
- `contracts/`: Smart contract code and configuration for Stardust.

## Configuration

Before running the application, you need to configure some settings:

1. Set up your Stardust API keys and smart contract configuration.

   Create a `.env` file in the `server/` directory and define the following variables:

   ```env
   STARDUST_API_KEY=your-api-key
   STARDUST_API_SECRET=your-api-secret
   STARDUST_CONTRACT_ADDRESS=your-contract-address
   ```

   Replace `your-api-key`, `your-api-secret`, and `your-contract-address` with your actual Stardust credentials and contract address.

2. Make sure to configure other environment-specific settings like database connection details if applicable.

## Usage

Once the application is set up and running, users can access the website and start minting their NFTs. The intuitive interface will guide them through the process, allowing them to upload files, add metadata, and finalize the minting.

## Contributing

Contributions to this project are welcome! If you want to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to the main repository's `main` branch.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to reach out to the project maintainers for any questions or issues.

Happy minting! 🚀🪙
