git clone https://github.com/gorsaribekyan/redis-cluster

docker compose up -d

docker exec -it redis-cluster-redis-node-2-1 bash

redis-cli -p 6379 -c

AUTH P@ssw0rd

CLUSTER NODES

set foo bar

get foo