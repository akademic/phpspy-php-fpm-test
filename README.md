# HOW TO USE

1. Change directory to this repository root
2. Run `docker-compose up -d`
3. Run `ps aux | grep php-fpm`
4. Pick proc_id of non-master process
5. Run `sudo phpspy -p {proc_id}`
6. Observe not working behavior


# TO STOP CONTAINER

Run `docker-compose down`
