# poetry-preview-docker-image
poetry 1.0 がリリースされる前に CircleCI で使うための Dockerfile

[Docker Hub](https://cloud.docker.com/repository/docker/515hikaru/poetry-preview)

```sh
cd src/
docker build -t 515hikaru/poetry-preview .
docker push 515hikaru/poetry-preview
```
