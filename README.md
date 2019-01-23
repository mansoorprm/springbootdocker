# springbootdocker


mvn install dockerfile:build

docker run -p 8090:8090 -t mansoor/employee-producer:latest

docker login --username=yourhubusername

docker images

docker tag local-image:tagname reponame:tagname
docker push reponame:tagname