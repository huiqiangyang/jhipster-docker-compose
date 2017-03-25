# jhipster-docker-compose

- git clone jhipster-docker-compose.yml

## Hey guys, In fllowing content you may need update [yhq] to your home files 

``` 
jhipster:
  image: jhipster/jhipster:latest
  privileged: false
  restart: always
  ports:
  - '8080'
  - '3001'
  - '9000'
  - '8081'
  - '8082'
  - '8083'
  - '9999'
  volumes:
  - /home/yhq/.m2:/home/jhipster/.m2
  - /home/yhq/jhipster:/home/jhipster/app
  environment:
  - PATH=/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/usr/bin:/home/jhipster/.yarn-global/bin:/home/jhipster/.yarn/bin:/home/jhipster/.config/yarn/global/node_modules/.bin


```


`docker-compose -f jhipster-docker-compose.yml up -d`

`docker ps -a`

`docker exec -it [cid] [jhipster] bach`

Tryed yourself! Goodluck for you! 
