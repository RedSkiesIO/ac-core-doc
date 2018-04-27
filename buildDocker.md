##Standardized build enviroment

### Build the docker container 
docker build . --tag atlas/buildcontainer

### Build the blockchain source
docker run -it -v /srv/us:/srv atlas/buildcontainer make

