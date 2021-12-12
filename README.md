# Ansible Role: a docker-compose'd Netbox

## General
This role includes extensive configuration(and adapted defaults) for the different services it uses(take a
look at defaults/main.yml) from the community [netbox-docker](https://github.com/netbox-community/netbox-docker):
 * Redis as an append-only-cache
 * A second redis, configured as usual(removable items)
 * Postgres as it's database
 * Netbox-worker

... and Netbox itself.


## ToDo
- [ ] configure multiple workers
- [ ] Better README pls
- [ ] Explain usage(besides having... the role... existent... i guess?)