# WordPress + MySQL Deployment with Docker Compose

This project demonstrates how to containerize and deploy a WordPress website using Docker Compose with a MySQL backend and support for custom themes.

# What's Included
- WordPress (latest)
- MySQL (v5.7)
- Docker Compose
- Custom theme mounting
- `.env` file for configuration
- Persistent volumes for data safety

# Project Structure
├── docker-compose.yml
├── .env
├── README.md
└── custom-theme/
└── mytheme/


# How to Run

```bash
# Clone this repository
git clone https://github.com/Emstev/cba_wordpress.git
cd wordpress-docker

# Start containers
docker-compose up -d

# Stop containers
docker-compose down

# Notes
Visit the app at: http://localhost:8080
Customize your WordPress theme in custom-theme/mytheme/

