# docker-compose-mariadb-phpmyadmin

Docker example with Apache, MariaDB 10.1, PhpMyAdmin and Php 7

Contribution to [jcavat](https://github.com/jcavat/docker-lamp) for his contribution :heart:.

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
