FROM redis:7-alpine
COPY docker/prod/redis/redis.conf /usr/local/etc/redis/redis.conf
HEALTHCHECK CMD redis-cli ping
