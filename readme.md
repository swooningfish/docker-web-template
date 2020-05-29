# Run command 
`docker-compose up -d --build`

# Other Useful Commands

## Remove Volums
`docker rm $(docker ps -a -q)`

## Remove images
`docker rmi $(docker images -q)`

## Restart Apache
`docker exec -it httpd httpd -k restart`