# Pull the Redis image

docker pull redis:latest
docker run --name local-redis -p 6379:6379 -d redis

# Run the notebook step by step
