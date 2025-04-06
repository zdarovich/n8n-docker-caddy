# n8n-docker-traefik-tailscale

Get up and running with n8n using Traefik and Tailscale:

1. SSH into your server
2. Clone the repository
3. Create required Docker resources
4. Start the services

```bash
git clone https://github.com/zdarovich/n8n-docker-caddy.git
cd n8n-docker-caddy

# Create required Docker resources
docker volume create tailscale
docker volume create tailscale-sock
docker volume create traefik
docker volume create n8n
docker network create tailscale-traefik

# Start the services
docker compose up -d
```
