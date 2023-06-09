# Implementing distributed Minio (Open source object storage - similar to S3)

## Getting Stated
1. Install docker & docker-compose
2. Create '.env' file and put in your credential (don't push to git, already added to .gitignore)
3. In .env define MINIO_ROOT_USER=<access-key-here> and MINIO_ROOT_PASSWORD=<secret-key-here>
4. Follow instruction of *How to Use* section


## How to use
Start
```
docker-compose up -d --force-recreate
```

Stop
```
docker-compose down
Ctrl + C
```
