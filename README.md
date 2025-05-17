# 🌊 Droplet: A Minimal, Secure, and Modern File-Storage Application

![Droplet Logo](https://example.com/logo.png)

Welcome to the Droplet repository! Droplet is a minimal, secure, and modern file-storage application designed for developers and users who value simplicity and security. This README will guide you through the installation, features, and usage of Droplet.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Minimal Design**: Droplet focuses on a clean and straightforward user interface, making file management easy.
- **Security**: Built with security in mind, Droplet ensures your files are safe with modern encryption methods.
- **Cross-Platform**: Works seamlessly on various platforms, thanks to Docker and Docker Compose.
- **Fast Performance**: Optimized for speed, ensuring quick file uploads and downloads.
- **Responsive UI**: Built with Tailwind CSS and Shadcn UI for a modern look and feel on all devices.

## Technologies Used

Droplet leverages a variety of technologies to deliver a robust application:

- **Frontend**: 
  - React
  - TypeScript
  - Tailwind CSS
  - Shadcn UI

- **Backend**:
  - Spring Boot 3
  - Spring Security
  - Spring Data JPA
  - Spring Data MongoDB

- **Database**:
  - PostgreSQL
  - MongoDB

- **Build Tools**:
  - Gradle
  - pnpm

- **Containerization**:
  - Docker
  - Docker Compose

## Installation

To get started with Droplet, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/lucascardoso508/droplet.git
   cd droplet
   ```

2. **Install Dependencies**:
   Navigate to the frontend and backend directories to install the required packages.

   For the frontend:
   ```bash
   cd frontend
   pnpm install
   ```

   For the backend:
   ```bash
   cd backend
   ./gradlew build
   ```

3. **Run the Application**:
   You can run the application using Docker Compose. In the root directory, execute:
   ```bash
   docker-compose up
   ```

4. **Access the Application**:
   Open your browser and go to `http://localhost:3000` to access the Droplet application.

5. **Download the Latest Release**:
   For the latest version of Droplet, visit the [Releases section](https://github.com/lucascardoso508/droplet/releases). Download the necessary files and execute them as instructed.

## Usage

Once the application is running, you can:

- **Upload Files**: Use the upload button to add files to your storage.
- **Download Files**: Click on any file to download it to your device.
- **Manage Files**: Organize your files into folders for better management.

## Contributing

We welcome contributions to Droplet! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your branch to your forked repository.
5. Create a pull request.

Please ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

Droplet is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For questions or feedback, please reach out to the maintainers:

- **Lucas Cardoso**: [GitHub Profile](https://github.com/lucascardoso508)

Feel free to explore the [Releases section](https://github.com/lucascardoso508/droplet/releases) for the latest updates and features.

---

Thank you for checking out Droplet! We hope you find it useful for your file storage needs.