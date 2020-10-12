## Description

Docker compose file

Run setup

`docker-compose -f {filename} up` 

Check log if contanier cannot start

`docker logs --tail 50 --follow --timestamps {container_name}` 

Remove all container

`docker stop $(docker ps -a -q)`
`docker rm $(docker ps -a -q)` 