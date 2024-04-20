# Installation

```
git clone https://github.com/diegox8x/self-hosted.git
cd sain-dest/portainer
```

A la hora de levantar el servicio dependerá del proxy inverso que hayas seleccionado. Si has elegido Caddy, simplemente,

```
docker compose up -d
docker-compose logs -f
```

