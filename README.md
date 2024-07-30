# Xendit Integration Backend

This repository contains a backend service to handle integration with Xendit using TypeScript.

## Overview

This project aims to provide a robust and scalable backend service for integrating with Xendit, a payment gateway API. The service is built using TypeScript and follows best practices for structure and maintainability. It includes essential functionalities such as creating invoices, handling payments, and managing configurations securely.

## Features

- **Invoice Management**: Create and manage invoices using Xendit API.
- **Payment Handling**: Seamlessly handle various payment methods supported by Xendit.
- **Configuration Management**: Securely manage and use configurations for Xendit integration.
- **Logging**: Comprehensive logging for monitoring and debugging.
- **Error Handling**: Robust error handling to ensure reliability.

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- npm (>= 6.x)
- Docker (optional, for containerized deployments)

### Installation

1. Clone the repository:

```sh
git clone https://github.com/your-username/xendit-integration-backend.git
cd xendit-integration-backend
```

2. Install dependencies:

```sh
npm install
```

3. Configure environment variables:

Copy the .env.example file to .env and update the values as needed.

```sh
cp .env.example .env
```

### Running the Application

To start the development server:

```sh
npm run dev
```

The server will start on the port specified in your .env file or default to 3000.

### Logging

The project uses a custom logger located at src/utils/logger.ts for logging information and errors.

### Contributing

```sh
1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes.
4. Commit your changes and push to your branch.
5. Create a pull request.
```