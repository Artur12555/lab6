
skrypt do uruchomienia:

start.sh


docker run -d --name traefik --network proxy -p 80:80 -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock traefik:latest --api.insecure=true --providers.docker


docker run -d --name traefik --network proxy -p 80:80 -p 8080:8080 -v /var/run/docker.sock:/var/run/docker.sock traefik:latest --api.insecure=true --providers.docker
