# Realtime Demo

This code is part of a 2 part blog series on building real-time web apps with Server-Sent Events.

- [Part 1](http://bayn.es/real-time-web-applications-with-server-sent-events-pt-1/)
- [Part 2](http://bayn.es/real-time-web-apps-with-server-sent-events-pt-2/)

## Installation

    npm install
    grunt

## Running with Docker

    docker-compose up







sudo yum update -y
sudo yum install git -y
git clone https://github.com/yingdi11/sse-realtimedemo-simonbaynes.git
cd sse-realtimedemo-simonbaynes
sed -i "s/localhost/$(hostname -f)/g" static/index.html

sudo yum update -y
sudo yum install -y gcc-c++ make
curl -sL https://rpm.nodesource.com/setup_18.x | sudo -E bash -
sudo yum install -y nodejs
npm install


sudo yum install -y docker
sudo service docker start
sudo systemctl enable docker
sudo usermod -aG docker ec2-user
sudo curl -L "https://github.com/docker/compose/releases/download/v2.21.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
sudo docker-compose up
