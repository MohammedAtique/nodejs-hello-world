# Simple Hello-World App
This is a simple Hello World app built with NodeJS.

## Installation
1. Run these commands to install the necessary tools
```
sudo apt update -y
sudo apt install docker.io docker-compose -y
sudo usermod -aG docker $USER
newgrp docker
```

2. Clone the repository
```
git clone https://github.com/MohammedAtique072/nodejs-hello-world.git
```

### Via Docker
1. Build the app
```
docker build -t hello-world .
```

2. Run the app
```
docker run -d -p 3000:3000 hello-world:latest
```

### Via Docker-Compose
1. Build the app
```
docker-compose up -d
```
