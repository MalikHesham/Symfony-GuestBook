# Symfony-GuestBook v5.3
## Installation
1. To install symfony ```$ wget https://get.symfony.com/cli/installer -O - | bash```
2. Clone the repo using ``$ git clone https://github.com/MalikHesham/Symfony-GuestBook ``
3. Run `` $ composer install `` to install the project dependencies 
4. Install docker ```$ curl -fsSL https://get.docker.com -o get-docker.sh``` then ```sudo sh get-docker.sh```
5. To validate that docker is installed ```$ sudo docker run hello-world ```
6. Install docker-compose ``$ sudo curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose``
then
`` $ sudo chmod +x /usr/local/bin/docker-compose``
7. OPTIONAL: make a symbolic link to /usr/bin using ```$ sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose ```
8. Change the docker-compose.yaml file in the repo then start docker compose in the background ``` $ sudo docker-compose up -d```
9. After the installation is completed, make sure everything is running fine using ``` $ docker-compose ps ```
10. Accessing the database using ```$ sudo symfony run psql```
