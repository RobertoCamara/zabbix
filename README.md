# zabbix

### Clone repository
git clone git@github.com:RobertoCamara/zabbix.git

### Create directories
cd zabbix

mkdir -p data/mysql protocolo/snmptraps protocolo/mibs

## Docker stack
docker stack deploy -c docker-compose.yaml NAME_STACK

## Docker compose

### Create and start containers
docker-compose up -d

### Stop and remove containers, networks, images, and volumes
docker-compose down
