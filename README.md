# redis
a Redis docker example

## examples

docker compose up -d --build

docker exec -it redis redis-cli
127.0.0.1:6379> info

docker exec -it redis sh
cd /
ls -l
exit

docker compose logs -f

docker compose down
