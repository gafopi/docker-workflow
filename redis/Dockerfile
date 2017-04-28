FROM redis:latest

# start redis with custom configuration
COPY redis.conf /usr/local/etc/redis/redis.conf
EXPOSE      6379
CMD [ "redis-server", "/usr/local/etc/redis/redis.conf" ]
