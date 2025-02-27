# AzurePentest is simulation lab of credential harvesting of Azure key vault via lateral movement of a windows VM in the Azure account. 
# Azure Pentesting Terraform Practice Lab

Welcome to the Azure Pentesting Terraform Practice Lab! This lab is designed to help security professionals and enthusiasts sharpen their penetration testing skills in an Azure environment using Terraform.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Lab Structure](#lab-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This practice lab is a hands-on environment for learning and practicing penetration testing techniques within Azure infrastructure. It leverages Terraform for infrastructure as code (IaC) to deploy a simulated Azure environment that includes various security vulnerabilities.

## Features

- **Infrastructure as Code:** The lab utilizes Terraform for defining and provisioning the Azure environment, enabling easy setup and teardown of the lab.
- **Realistic Scenarios:** The lab includes realistic Azure configurations with intentional security vulnerabilities, providing a practical environment for penetration testing.
- **Diverse Vulnerabilities:** Explore a range of common Azure misconfigurations and vulnerabilities, including identity and access management issues, network security flaws, and more.
- **Detailed Documentation:** Comprehensive documentation guides users through the lab setup, scenarios, and recommended penetration testing methodologies.

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- Azure subscription
- Terraform installed locally
- Azure CLI installed locally
- Git for cloning this repository

## Getting Started

1. Clone this repository:

    ```bash
    git clone https://github.com/arkcarrier/AzurePentest.git
    cd AzurePentest
    ```

2. Follow the [lab setup instructions](docs/setup.md) to deploy the Azure environment using Terraform.

3. Explore the [detailed documentation](docs) for information on various scenarios and penetration testing methodologies.

## Lab Structure

The lab is structured into different modules, each representing a specific Azure service or configuration. The [lab structure documentation](docs/lab-structure.md) provides an overview of each module and its associated vulnerabilities.

## Usage

Follow the guidance in the documentation to perform penetration testing on the Azure environment. Share your findings and improvements by opening issues or submitting pull requests.

## Contributing

Contributions are welcome! Feel free to open issues, submit pull requests, or provide feedback. Check out the [contribution guidelines](CONTRIBUTING.md) for more details.

## License

This project is licensed under the [MIT License](LICENSE).
