# Ubuntu-Docker-Traefik-Media-Server
The template files for my current media server rig.

Uses Docker and Docker-Compose to manage the config and deployment of the microservices I use.
Uses Traefik v2 to host all services behind a reverse proxy with service provisions done at the origin server, rather than at the DNS provider.
Uses Cloudflare for all domain routing, and updating DNS records for dynamic IPs.
