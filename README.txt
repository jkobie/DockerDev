 1708  sudo apt-get install docker-ce
 1709  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
 1711  sudo add-apt-repository    "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 1714  sudo add-apt-repository    "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 1718  sudo apt-get install docker-ce
 1719  docker
 1720  docker volume create portainer_data
 1721  sudo usermod -a -G docker jkobie
 1722  docker volume create portainer_data
 1783  sudo docker run hello-world
 1784  docker volume create portainer_data
 1785  docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer
 1786  docker ps
 1787  sudo docker run -d -p 9000:9000 portainer/portainer
 1788  docker ps
 1789  docker run -d -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data portainer/portainer
 1790  docker ps
 1793  docker-compose –version
 1794  docker-compose –versionsudo apt install docker-compose
 1795  sudo apt install docker-compose
 1796  docker logs hass --since 5m -f
 1797  docker logs 
 1798  docker logs homeassistant
 2006  docker --version
 2007  docker info
 2008  docker run hello-world
 2009  docker container ls --all
 2011  docker --version
 2012  docker run hello-world
 2022  docker build --tag=friendlyhello .
 2025  docker run -p 4000:80 friendlyhello
 2028  docker build --tag=friendlyhello .
 2029  docker run -p 4000:80 friendlyhello
 2031  docker build --tag=friendlyhello .
 2032  sudo service docker restart
 2033  docker build --tag=friendlyhello .
 2034  docker run -p 4000:80 friendlyhello
 2035  docker container ls
 2036  docker run -d -p 4000:80 friendlyhello
 2037  docker container ls
 2038  h | grep docker
 2039  docker container ls --all
 2040  docker container ls\
 2041  docker container ls
 2042  docker container stop 39c1f0d0a187
 2043  docker container ls
 2044  docker container ls --all
 2045  docker login
 2046  docker tag friendlyhello jkobie/get-started:part2
 2047  docker image ls
 2048  docker push get-started:part2
 2049  docker push jkobie/get-started:part2
 2050  docker run -p 4000:80  jkobie/get-started:part2
 2051  h | grep docker
 2053  h | grep docker > README.txt
