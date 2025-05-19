# Setting Up a Laravel Development Environment with Docker and Docker Compose

A comprehensive guide to setting up a robust Laravel development environment using Docker and Docker Compose, featuring multiple services and best practices for containerization.


<p align="center">
<img src="https://miro.medium.com/v2/resize:fit:700/1*VvKZZV8uXmlrBhxwaWFS0A.png" alt="Intro" />
</p>

More information at - 
https://medium.com/@murilolivorato/setting-up-a-laravel-development-environment-with-docker-and-docker-compose-a-step-by-step-5e37670ae640


## Overview

This project demonstrates how to set up a complete Laravel development environment using Docker, including:
- PHP 8.2 with FPM
- Nginx web server
- MySQL 8.0 database
- Mailhog for email testing
- PhpMyAdmin for database management
- Docker Compose for service orchestration

## Features

- Containerized Laravel development environment
- Multiple service integration
- Email testing capabilities
- Database management interface
- Easy service scaling
- Environment isolation
- Development and production configurations
- Hot-reloading support

## Prerequisites

- Docker Engine
- Docker Compose
- Git
- Basic understanding of Laravel
- Basic understanding of Docker concepts
- Administrative privileges on your system

## System Requirements

- Compatible operating system (Linux, macOS, or Windows)
- Administrative privileges
- Internet connection
- Minimum 4GB RAM (8GB recommended)
- 20GB free disk space

## Installation

### 1. Install Docker

#### For Windows:
1. Download Docker Desktop from [Docker's official website](https://www.docker.com/get-started)
2. Run the installer
3. Enable Hyper-V when prompted
4. Follow the installation wizard
5. Restart your computer

#### For macOS:
1. Download Docker Desktop for Mac
2. Drag Docker to your Applications folder
3. Open Docker from Applications
4. Follow the setup wizard


## Run those commands
- docker-compose up -d --build
- docker-compose run --rm composer install
- docker-compose run --rm artisan key:generate



## 👥 Author

For questions, suggestions, or collaboration:
- **Author**: Murilo Livorato
- **GitHub**: [murilolivorato](https://github.com/murilolivorato)
- **linkedIn**: https://www.linkedin.com/in/murilo-livorato-80985a4a/

## 🙏 Acknowledgments

- FastAPI documentation
- React documentation
- Kubernetes documentation
- Docker documentation
- Open source community

## 📸 Screenshots

### Running Commands
![Running Commands](https://miro.medium.com/v2/resize:fit:700/1*_gOC9UlGPgymCsMJYLuCcA.png)

### Created
![Created](https://miro.medium.com/v2/resize:fit:700/1*tE9oMj91IvMDuXrjvh_NFA.png)

### Access the Database
![Access the Database](https://miro.medium.com/v2/resize:fit:700/1*3WSFU3DEHF5nPbuKKNe7uQ.png)

### Laravel App is Running
![Access the Database](https://miro.medium.com/v2/resize:fit:700/1*q9vN15zXnPXbHxqUOS0SfA.png)

<div align="center">
  <h3>⭐ Star This Repository ⭐</h3>
  <p>Your support helps us improve and maintain this project!</p>
  <a href="https://github.com/murilolivorato/laravel_docker_enviroment/stargazers">
    <img src="https://img.shields.io/github/stars/murilolivorato/laravel_docker_enviroment?style=social" alt="GitHub Stars">
  </a>
</div>
