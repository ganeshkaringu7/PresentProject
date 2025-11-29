docker pull redis
docker run --name my-redis -d redis
docker images
docker ps
docker ps -a
docker exec -it my-redis redis-cli
docker stop my-redis
docker ps -a
docker start my-redis
docker ps -a
docker stop myredis
docker rm my-redis
docker ps -a
docker rmi redis
docker images
FROM redis:latest
CMD ["redis-server"]
 docker build -t redisnew  .
docker run --name myredisnew -d redisnew
docker images
docker ps -a
 docker stop myredisnew

 docker login
docker commit 0e993d2009a1 budarajumadhurika/redis1

docker push budarajumadhurika/redis1

docker images

docker push budarajumadhurika/redis1

docker rm 0e993d2009a1

 docker rmi budarajumadhurika/redis1

docker images
docker logout

docker pull budarajumadhurika/redis1

 docker run --name myredis -d budarajumadhurika/redis1

docker images

 docker exec -it myredis redis-cli

docker ps -a

docker stop myredis

docker rm 50a6e4a9c326

 docker images

docker rmi budarajumadhurika/redis1
