# spring-boot-redis

## docker
1. docker ps 
2. docker run -p 6379:6379 --name redis_boot -d redis 
3. docker exec -i -t redis_boot redis-cli

## redis
1. keys *
2. get name
3. hget accounts:55ce7f3d-3798-4c37-8b57-ca78a187dfa8 username 
4. hgetall accounts:55ce7f3d-3798-4c37-8b57-ca78a187dfa8