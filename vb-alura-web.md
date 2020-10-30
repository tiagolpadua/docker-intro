# Orientações VirtualBox Alura Web

```bash
sudo systemctl stop tomcat
sudo systemctl disable tomcat
sudo snap install docker

https://www.digitalocean.com/community/questions/how-to-fix-docker-got-permission-denied-while-trying-to-connect-to-the-docker-daemon-socket

sudo groupadd docker

sudo usermod -aG docker ${USER}

Reiniciar a máquina

sudo curl -L https://github.com/docker/compose/releases/download/1.27.4/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
```
