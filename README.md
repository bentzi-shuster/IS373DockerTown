# IS373DockerTown
- docker run -it fedora  - run container
- docker stop containerID - stop container
- docker ps - list running containers
- docker pull fedora - pull image (fedora in this case)
- docker kill containerID - kill container (diffrerent from stop in that it doesn't give it time to shut down)
- docker images - list images
- docker rm containerID - remove container
- docker rmi imageID - remove image
- docker images rm imageID - remove image
- docker stats - list stats of running containers
- docker run --name containerName -it containerType - run container with name
- docker run -dp 8080:80 containerType - run container with port mapping (8080 is host port, 80 is container port)
- docker start containerID - start container
- docker exec -it containerID bash - run bash in container


docker run -v ${pwd}:/home/myuser -e QR_CODE_IMAGE_DIRECTORY="homework" -e QR_CODE_DEFAULT_FILE_NAME="GmailQrCOde.png" -e QR_CODE_DEFAULT_URL="https://www.gmail.com" qrcode