# Semaphore UI

This project aims to simplify the management and deployment of Semaphore CI/CD pipelines using Ansible. It provides a collection of Ansible roles and playbooks to automate common tasks, such as:

- Creating and updating projects
- Managing secrets and environment variables
- Defining and running workflows
- Integrating with other tools and services

## Features

- **Declarative Infrastructure:** Define your Semaphore pipelines as code using Ansible playbooks. This allows for version control, reproducibility, and easier collaboration.
- **Simplified Management:** Automate repetitive tasks, such as creating projects, managing secrets, and triggering workflows.
- **Extensibility:** Easily extend the provided roles and playbooks to fit your specific needs.
- **Improved Collaboration:** Using Ansible allows for consistent and transparent management of your Semaphore CI/CD pipelines across your team.

## Getting Started

### Prerequisites

- Docker and Docker Compose installed.

### Installation

1. Clone this repository.

2. Run `docker-compose up -d` to start the Semaphore container.

### Usage

You can change environment variables in the `.env` file.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
