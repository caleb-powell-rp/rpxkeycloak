# rpx docker theme

## To run this container standalone

Build the container

```sudo docker build -t rpx/keycloak .```

Run the container

```sudo docker run -d -p 8080:8080 -e DB_VENDOR=h2 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin rpx/keycloak```
