# grails2.3.9
grails2.3.9 is created based on https://hub.docker.com/r/mozart/grails/

Map you grails project to /app, run as below:
docker run --rm -v /root/app/www:/app:rw -p 8090:8090 --name grails lixiayuan/grails2.3.9 run-app

