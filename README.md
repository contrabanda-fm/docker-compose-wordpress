# docker-compose-wordpress

Docker compose files for wordpress + mariadb

# Usage

1. Copy example '.env' file:

```
cp .env.example .env
```

2. (Optional) Adjust settings, such as host path for volumes, "VOLUME_DB" and "VOLUME_WORDPRESS"

3. Start the environment

```
sudo docker-compose up -d
```

4, Test

If you didn't changed any default variable in '.env' file, point your browser to:

http://localhost:8000

You should see the wordpress installation page

5. Stop

```
sudo docker-compose down
```
