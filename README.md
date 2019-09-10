# ZabbixYaml
- This only works on ubuntu for now
## How to use
run commands

sudo apt -y install docker.io docker-compose

sudo ufw allow 80/tcp
sudo ufw allow 443/tcp
sudo ufw allow 3306/tcp

clone this repo to desired location and navigate to the created ZabbixYaml folder created
sudo docker-compose up -d

then open localhost in preferred browser
