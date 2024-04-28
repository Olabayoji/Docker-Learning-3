# Docker-Learning-3

## Overview

This project aims to solidify understanding of Dockerized environments by learning to develop PHP applications, specifically tailored for Laravel. The project utilises Docker containers for Nginx, PHP, MySQL, and Composer, providing a portable and consistent development environment across different systems.

## Requirements

To use this project, ensure that you have the following software installed on your system:

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Olabayoji/Docker-Learning-3.git

2. Navigate to the project directory:
   ```bash
    cd Docker-Learning-3

3. Run the following command to generate the Laravel project in the `src` folder:
   ```bash
    docker-compose run --rm composer create-project --prefer-dist laravel/laravel .


4. Build and start the Docker containers:
   ```bash
    docker-compose up -d
    Note: The '-d' flag runs the containers in detached mode.

5. Access your application in a web browser at `http://localhost:8000`.

## Directory Structure
- **src**: Contains the application code.
- **env**: Contains environment configuration files.
- **nginx**: Contains Nginx configuration files.
- **dockerfiles**: Contains Dockerfile configurations for PHP and Composer.

