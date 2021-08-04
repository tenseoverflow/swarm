# AdGuardHome DNS with Unbound

## Prerequisite

Traefik proxy installed in Docker swarm as a proxy.

## Deployment

* `git clone https://`
* `cd ./dns`
* `docker deploy -c docker-compose.yml dns`

Update using the `docker deploy` command.