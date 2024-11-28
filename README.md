### Gateway Api Repo

This repository is just a way to up all necessary micro services built using docker compose, by using that,
we can up all necessary micro services and use kong as a gateway api to receive requests and manage to the right micro service.

This is a simulation of a micro service application.

### Requirements

- Docker and Docker compose cli.
- Clone this repository and the micro services repositories (them need to be in the same dir)

### How to run

- Install Docker and Docker compose cli if you dont have already installed.
- Clone this repository and all micro services repositories too.
- Go to gateway api repository.
- Copy the file `.env.sample` and rename to `.env`
- Fill with all necessary envs.
- Run the command `docker compose up -d`.
- Use an http client send request (remember to take a look on `request.http` file)