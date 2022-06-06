# Docker environment with php 8.1
<hr>
<div style="display:inline-block">
<img align="center" alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white"/>
<img align="center" alt="Nginx" src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/>
<img align="center" alt="MySQL" src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white"/>
<img align="center" alt="Redis" src="https://img.shields.io/badge/redis-CC0000.svg?&style=for-the-badge&logo=redis&logoColor=white"/>
</div>

Development environment with php 8.1-fpm, Nginx, MySQL and Redis

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

Docker and docker-compose installed

### Installing

A step by step series of examples that tell you how to get a development env running

Clone the project and go to project folder

```
git@github.com:roinuj16/docker_php_8_1.git
cd docker_php_8_1
```

To check all available commands run the command

```
make 
```

Initialize the ./make/.env and ./docker.env files

```
make make-init
make docker-init
```

## Authors

* **Edson Junior** - [Roinuj16](https://github.com/roinuj16)
