# services-docker


## Deploy Order

1. [Main System](docker-compose.yml): Portainer, Watchtower, weavescope
2. [Home System](docker-compose.home.yml): Nginx Proxy, Mysql db for nginx proxy, unifi Controller
3. [Tyler System](docker-compose.tyler.yml): wordpress, phpmyadmin, mysql db for wordpress
4. 