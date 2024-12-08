

Make sure your Raspberry Pi is up-to-date:
    
    sudo apt update && sudo apt upgrade -y

Install Docker

    curl -fsSL https://get.docker.com -o get-docker.sh
    sudo sh get-docker.sh

Add your user to the Docker group

    sudo usermod -aG docker $USER
    newgrp docker

Install Docker Compose
    
    sudo apt install docker-compose

    

