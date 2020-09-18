# wordpres-docker-compose
A docker compose file that implements WordPress (CMS), MariaDB (Database) and PhpMyAdmin (DB access)

## Requirements
Ensure you have Docker and Docker Compose installed on your system.

Clone the repository.

## Installation
Open a terminal and cd to the folder in which docker-compose.yml is saved and run:
`docker-compose up`
This will build and run the containers. To access the WordPress site, visit `http://localhost:8000` .

## Usage
### Starting Containers
To start the containers, you run the following command in the terminal.

`docker-compose start`

### Stopping containers

`docker-compose stop`

### Removing containers
To stop and remove all containers run the following command.

`docker-compose down`

### Wordpress
To access the WordPress site, visit `http://localhost:8000` .

### PhpMyAdmin
To access PhpMyAdmin, visit `http://localhost:8080` .
