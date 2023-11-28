# LAMP Stack
## Local development environment build with Docker Compose

A basic LAMP stack environment built using Docker Compose. It consists of the following:
- PHP
- Apache
- MySQL
- phpMyAdmin
- Redis (TODO)
- RabbitMQ (TODO)

#### PHP Versions:
- 7.4.x
- 8.1.x
- 8.2.x

#### MariaDB Versions:
- N/A

#### MySQL Versions
- 8

### Installation
- Clone this repository on you local computer
- Configure .env as needed
- Run the ```docker-compose up -d```.

```bash
git clone https://github.com/jacekachtelik/lamp-docker.git
cd docker-compose-lamp/
cp sample.env .env
docker-compose up -d
```
- Visit ```http://localhost```


> ### Source project:
> [Docker Compose LAMP](https://github.com/sprintcube/docker-compose-lamp)

