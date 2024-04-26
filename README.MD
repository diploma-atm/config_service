##Build docker image

### `gradlew bootBuildImage`

Если нужно изменить тег, то нужно зайти в build.gralde на 17 строке изменить на нужное значение


docker push registry.gitlab.com/komek-112/config-server


docker push registry.gitlab.com/komek-112/config-server:latest