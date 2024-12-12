Deployment condition .

MVN clean install -DskipTests:true

run docker file it will create docker image

docker build -t twitter-app .

create container 

docker run -itd --name twitter-app -p 8090:8080 imagename

