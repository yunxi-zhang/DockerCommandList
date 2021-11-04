# DockerCommandList
This repo shows common commands used for docker

1. Delete all containers<br>
`docker rm $(docker ps -aq)`
2. Delete all dangling images<br>
`docker rmi $(docker images -f "dangling=true" -q)`