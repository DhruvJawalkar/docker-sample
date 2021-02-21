# docker-sample

## useful docker commands
docker run -v /your/dir:/var/lib/mysql -d mysql:5.7 <br/>
<br/>
docker build -t webserver . <br/>
docker run --rm -it -p 8082:80 webserver <br/>
docker run --rm -e diameter=1.5 learnbook/jsparam <br/>
<br/>
docker tag webserver learnbook/webserver <br/>
docker login <br/>
docker push learnbook/webserver <br/>
<br/>
.dockerignore file <br/>
FROM nginx:1.15-alpine <br/>

## sample app with docker-compose 
https://docs.docker.com/compose/gettingstarted/