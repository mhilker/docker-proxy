# Docker Proxy

[![Software License][ico-license]](LICENSE.md)

Docker Proxy Server with [jwilder/docker-gen](test) and [jrcs/letsencrypt-nginx-proxy-companion](letsencrypt-companion).

## Installation

Get the latest `nginx.tmpl` file.

```bash
wget https://raw.githubusercontent.com/jwilder/nginx-proxy/master/nginx.tmpl
```

# Start

Start the stack with `docker stack deploy`:

```bash
docker stack deploy proxy --compose-file docker-compose.yml
```

# Stop

Start the stack with `docker stack rm`:

```bash
docker stack rm proxy
```

[nginx-proxy]: https://github.com/jwilder/nginx-proxy
[letsencrypt-companion]: https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion
