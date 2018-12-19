# zabbix

### Clone repository
git clone https://github.com/RobertoCamara/zabbix.git

### Create directories
mkdir -p var/zabbix/data var/zabbix/protocolo/snmptraps var/zabbix/protocolo/mibs

## Docker stack (Deploy com Swarm)
docker stack deploy -c stack.yaml NAME_STACK

## Docker compose (Deploy sem Swarm)

### Create and start containers
docker-compose up -d

### Stop and remove containers, networks, images, and volumes
docker-compose down
