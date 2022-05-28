# servers
how i run stuff

## Nebula

Installer: https://gist.github.com/farberbrodsky/eccbe46a449de43e6548138bda06b154/

gives me cool 100.22.22.xxx ips for communication between servers.

if using ufw: sudo ufw allow in on nebula1

## Docker

`/etc/docker/daemon.json`: set to `{"iptables": false}`

otherwise it opens the port to the whole world...
