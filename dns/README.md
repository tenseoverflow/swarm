# AdGuardHome DNS with Unbound

## Prerequisite

Traefik installed in Docker swarm as a proxy.

## Deployment

* `git clone https://github.com/tenseoverflow/swarm`
* `cd ./dns`
* `docker deploy -c docker-compose.yml dns`

I'd recommend changing the web interface port to `3000`.

Update using the `docker deploy` command.