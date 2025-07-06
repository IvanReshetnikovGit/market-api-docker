📦 Market API — Docker Compose Setup

This project allows you to deploy the API and MySQL database with a single command using Docker Compose.
🚀 How to Run

    Make sure Docker and Docker Compose are installed

    Download or clone this project

    Run the following command in the terminal:

    docker-compose up
    
    result would be there: http://localhost:5000/swagger/index.html

📡 What's Included

    MySQL 8 (port 3307)

    ASP.NET Web API from the image govordin/market-api:latest (port 5000)

    Automatic database migrations on startup

    Environment variables for the API are preconfigured

🛑 How to Stop

docker-compose down

🐳 Requirements

    Docker

    Docker Compose

ℹ️ Note

The API image must be published to Docker Hub under the name:

govordin/market-api:latest

If you want to build the image locally instead, replace the image: section with build: in your docker-compose.yml.
