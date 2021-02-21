# docker-sample

## useful docker commands
### to share volumes
docker run -v /your/dir:/var/lib/mysql -d mysql:5.7 <br/>
<br/>
### to build an image with specific name, expose port, set env variable
docker build -t webserver . <br/>
docker run --rm -it -p 8082:80 webserver <br/>
docker run --rm -e diameter=1.5 learnbook/jsparam <br/>
<br/>
### to push an image to registry
docker tag webserver learnbook/webserver <br/>
docker login <br/>
docker push learnbook/webserver <br/>
<br/>

.dockerignore file <br/>
FROM nginx:1.15-alpine (lighter image version)<br/>

## sample app with docker-compose 
https://docs.docker.com/compose/gettingstarted/

https://www.educative.io/courses/docker-for-developers
