# drone_gogs_docker
Docker Compose for drone.io (CI-CD) and gogs (git service)

# Prerequisites

- Docker (started) and docker-compose (just install Docker for Desktop if you are on laptop) 

# Quickstart

1. Clone repo `git clone https://github.com/datafuel/drone_gogs_docker.git`
2. Run `cd drone_gogs_docker`
3. Rename **.env.example** to **.env** and replace dummy values with yours
4. Run `docker-compose up` then access the services
  
## Access services
  - gogs : http://localhost:3030
  - Drone server : http://localhost:80