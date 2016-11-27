# GraphX tutorial

## Docker image

`docker pull dylanmei/zeppelin`

Go to __Running__ (or if you are a Windows user or do not have `docker-compose` go to __Running without Docker Compose__)

--

### Running

1. Clone the repository: `https://github.com/Ninani/GraphX-tutorial.git`
2. `cd GraphX-tutorial`
3. Run with Docker Compose: `docker-compose up`
4. Your Zeppelin notepad will be running at `http://${YOUR_DOCKER_HOST}:8080`



### Running without Docker Compose

1. Run docker: `docker run --rm -i -t -p 8080:8080 dylanmei/zeppelin /bin/bash`
2. `wget https://github.com/Ninani/GraphX-tutorial/archive/master.zip`
3. `unzip master.zip`
4. `chmod 755 run`
5. `./run`
6. Your Zeppelin notepad will be running at `http://${YOUR_DOCKER_HOST}:8080`
