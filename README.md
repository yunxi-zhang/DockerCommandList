# Docker Command List
This repo shows common commands used for docker

1. Delete all containers<br>
`docker rm $(docker ps -aq)`
2. Delete all dangling images<br>
`docker rmi $(docker images -f "dangling=true" -q)`

# NPM Command List
1. Show all symbolic links in node
`npm ls -g --depth=0 --link=true`