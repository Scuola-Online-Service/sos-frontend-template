# sos frontend template

## Requirements
- Docker (https://docs.docker.com/install/)
- docker-compose (https://docs.docker.com/compose/install/)

## Development instructions
1. Start docker daemon
2. Copy .env.sample to .env and change env variables
3. Run `docker-compose up`
4. The dev server will run on `http://localhost:8000`

NB: to log into the Joomla container run `docker exec -it sos-frontend-template_web_1 bash`

To force kill all the containers run `docker-compose down -v`. 