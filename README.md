# How to

How to run this Dockerized example app

## Build image

`docker image build -t reactexample .`

## Run container

`docker run -dp 5050:3000 --name new_container_name reactexample`

## In Browser

type in `localhost:5050`

## If sucessfull

Init react app will be shown