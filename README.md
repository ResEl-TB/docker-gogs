# resel/gogs
Customized gogs intance for resel

## Run
```bash
git clone https://github.com/ResEl-TB/docker-gogs.git
docker-compose up -d
```

Note: Please change defaults passwords of the DB in docker-compose.yml file.

## Tips
Install docker-compose as a container : https://docs.docker.com/compose/install/#install-as-a-container

Forward on premise port to local VM : `ssh -nNT -R 0.0.0.0:4222:localhost:42 proxy`

