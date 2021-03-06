# Docker-Compose File generator for JHipster applications

## Usage
This generator will check your subdirectories and find all the microservices and gateways you generated.
Then, it will generate a docker-compose.yml file which will run all those applications in one simple command :
```bash
docker-compose up
```

## Installation

This requires JHipster version greater than 3.0.
Clone this project, then run

```bash
npm link
```

Then go into a directory (we advice to create a directory alongside the applications directories) and run:

```bash
yo jhipster-docker-compose
```

Launch the registry first by running:
```bash
docker-compose up -d jhipster-registry
```

Wait a minute and finally, you can launch all the applications by doing
```bash
docker-compose up -d
```
