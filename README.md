# Heroku-Docker-Nginx-MinIO

https://github.com/minio/minio

## Manual deployment

You will need to create a Heroku account and install the Heroku CLI, eg.
`brew install heroku`.

```
heroku container:login
heroku create
heroku container:push web
heroku container:release web
heroku open
```

## Usage

Default credentials:
```
minioadmin:minioadmin

Storage resets on each deploy :)
```
