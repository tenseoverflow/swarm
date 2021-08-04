# AdGuardHome DNS with Unbound

## Prerequisite

Traefik installed in Docker swarm as a proxy.

## Deployment

* `git clone https://github.com/tenseoverflow/swarm`
* `cd ./dns`
* `docker deploy -c docker-compose.yml dns`

Update using the `docker deploy` command.