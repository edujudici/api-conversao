# INFO 
- Api para converter de celsius para fahrenheit e fahrenheit para celsius

## Instalando as dependências

    $ npm install

## Executando o projeto local

    $ node index.js

## Acessando o projeto no browser

    - http://localhost:8080/celsius/0/fahrenheit
    - http://localhost:8080/fahrenheit/0/celsius

## Build

    $ docker build -t edujudici/api-conversao:v1 .

## Push

    $ docker push edujudici/api-conversao:v1

## Tag

    $ docker tag edujudici/api-conversao:v1 edujudici/api-conversao:latest

## Push Tag

    $ docker push edujudici/api-conversao:latest

## Pull

    $ docker pull edujudici/api-conversao:v1

## Run

    $ docker container run -d -p 8080:8080 edujudici/api-conversao:v1
  

## Docker Hub

- https://hub.docker.com/r/edujudici/api-conversao

``` 
➜ docker container ls

CONTAINER ID        IMAGE                         COMMAND                  CREATED             STATUS              PORTS                    NAMES
4f0b5093e89a        edujudici/api-conversao:v1   "docker-entrypoint.s…"   10 minutes ago      Up 10 minutes       0.0.0.0:8080->8080/tcp   serene_mclaren
```
