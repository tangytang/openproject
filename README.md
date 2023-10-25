# OpenProject Deploy

Recipes and examples for deploying OpenProject.

* [Docker Compose](./compose/)
* [Kubernetes](./kubernetes/)



### Top Tips

#### start from scratch
- docker-compose stop 
- docker-compose down
- docker-compose down --volumes
- ensure `docker-compose.override.yml` file is added

# Activate composeX Inside a python virtual environment
python3 -m venv venv
source venv/bin/activate
pip install pip -U
pip install ecs-composex

## Additional commands
source venv/bin/activate

### Starting
OPENPROJECT_HTTPS=false docker-compose up -d

### Stopping
docker-compose down
