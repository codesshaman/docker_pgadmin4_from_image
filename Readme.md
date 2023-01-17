# Official postgresql image inside of docker container

Install:

``git clone https://github.com/codesshaman/docker_pgadmin4_from_image.git``

Build:

``make build``

or

``docker-compose up -d --build``

Connect in pgadmin to:

``http://your_host:5432``

Down:

``make down``

or

``docker-compose down``

Up:

``make``

or

``docker-compose up -d``

### Connect in the browser:

```
http://127.0.0.1:8432
```