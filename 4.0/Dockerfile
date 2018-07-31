FROM redis:4.0
COPY ./redis.conf /usr/local/etc/redis/redis.conf

RUN touch /var/log/redis/redis-server.log
RUN chmod 777 /var/log/redis/redis-server.log

EXPOSE 6379

CMD ["redis-server", "/usr/local/etc/redis/redis.conf"]