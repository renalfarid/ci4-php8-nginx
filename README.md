# Docker PHP-FPM 8.3 & Nginx 1.24 on Alpine Linux

This project sets up a Docker container running Alpine Linux with Nginx, PHP 8.3, PHP-FPM, and Composer. The container is configured to serve a PHP application located in the `/var/www/html` directory.

## Prerequisites

- Docker installed on your machine.

## Getting Started

### Clone the Repository

First, clone the repository to your local machine:

```sh
git clone https://github.com/renalfarid/ci4-php8-nginx.git
cd ci4-php8-nginx
docker build -t <image_name> . --no-cache
docker run -d -p 80:80 <image_name>
```

For dev CI4 source Code : /src

Open browser : http://localhost
