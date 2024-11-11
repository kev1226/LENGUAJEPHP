# Project in php

# Steps to run the project

# 1. Clone the Repository

# Go to the terminal cd LANGUAGE-PHP in the terminal

# 2. Build the Docker image

docker build -t php-docker .

# 3. Run the Docker Container

docker run -p 8080:80 php-docker

# Note: The application will be accessible at http://localhost:8080
