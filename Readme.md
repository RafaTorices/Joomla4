# Joomla Docker Compose
This is a docker-compose file for Joomla. It uses the official Joomla image and the official MySQL image.

## Versions

| Software | Version                                                  |
| -------- | -------------------------------------------------------- |
| Joomla   | Joomla! 4.4.2 Stable [ Pamoja ] 9-January-2024 16:00 GMT |
| MySQL    | 8.0                                                      |
| PHP      | 8.1.27                                                   |


## Requirements
- Docker
- Docker Compose

## Usage
1. Clone this repository
2. Run `docker-compose up -d`
3. Open your browser and go to `http://localhost:8080`
4. Follow the Joomla installation instructions
5. Use `http://localhost:8080` as the site URL
6. Use `http://localhost:8080/administrator` as the admin URL

## Configuration
You can change the MySQL root password and the Joomla database name, user, and password by editing the `docker-compose.yml` file.

## Author

👤 **Rafael Torices**
