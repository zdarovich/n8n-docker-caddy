# n8n-docker-caddy

Get up and running with n8n:

1. SSH into your server
2. Git clone
3. 


```bash
git clone https://github.com/zdarovich/n8n-docker-caddy.git
cd n8n-docker-caddy
docker volume create caddy 
docker volume create tailscale 
docker volume create n8n
docker network create tailscale-caddy
docker compose up -d
```
