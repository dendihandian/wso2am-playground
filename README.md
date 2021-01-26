# WSO2 Api Manager Playground

A docker-composed wso2 api manager configuration for your local development, learning and experiment. Inspired by Laradock repository.

## How to run
1. Duplicate the `wso2am/deployment.toml.example` into `wso2am/deployment.toml.example`
2. Run `docker-compose up -d`

## How to enter the bash console
```
docker-compose exec wso2am bash
```
or
```
docker exec -it wso2am-playground_wso2am_1 bash
```



## Copying the config from the container with latest image

```
docker cp wso2am-playground_wso2am_1:/home/wso2carbon/wso2am-3.2.0/repository/conf/deployment.toml ./wso2am/deployment.toml.example
```