## TL;DR

## Usage

```shell
git clone https://github.com/Orbital-Curvify/Curvify.git && cd Curvify

# Setup
docker-compose run frontend yarn
docker-compose run backend bin/rails db:create db:migrate

# Start
docker-compose up -d

# Open yaichi reverse proxy
open http://localhost:80 # You'll see yaichi page, then click any app

# Open frontend
open http://frontend.localhost

# Check backend API
curl -H 'Host: backend.localhost' http://localhost/greetings/hello
```

## Motivation
Move yourself up the bell curve in different aspects

## Features
User Authentication
Filters





### Tech Stack

React + Rails + PostgreSQL + Docker Compose + BootStrap + MUI + NGINX


### References
https://create-react-app.dev/
https://github.com/ohbarye/rails-react-typescript-docker-example.git


