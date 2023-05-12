---

# Docker Template for PHP 8, Apache, MariaDB, and phpMyAdmin

Welcome to the Docker template for PHP 8, Apache, MariaDB, and phpMyAdmin!

This repository contains the necessary files to create a Docker container that is ready to use. It includes PHP 8, Apache, MariaDB, and phpMyAdmin, making it easy to set up a development environment for PHP web applications.

## Usage

To use this Docker template, follow these steps:

1. Clone this repository to the desired directory:

   ```
   git clone https://github.com/your-username/docker-template-php8-apache-mariadb-phpmyadmin.git
   ```

2. Open `docker-compose.yml` and `docker.env` files in your code editor.

3. Replace all occurrences of `template` with the desired name for your project (be consistent with the naming).

4. Navigate to the cloned directory in the terminal and run:

   ```
   docker-compose up
   ```

5. Docker will create the container for you. However, make sure that the localhost port number is not already in use. If a container is already running on port 80:80, you will need to either stop it or change the port number in the `docker-compose.yml` file.

## Credits

This Docker template was created by Laurent.

---
