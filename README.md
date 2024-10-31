# Th0b cloud

_New future era of my own home server._

## General informations

- Domain name: [th0b.cloud](https://www.name.com/domain/search/th0b.cloud)

## Mail services

- Using [emailprofi](https://emailprofi.seznam.cz/) by Seznam.
- Email boxes:
  - noreply@th0b.cloud _(noreply purpose)_
  - contact@th0b.cloud _(contact purpose)_
  - admin@th0b.cloud _(admin purpose)_

## Hardware

## VPS

- Because I don't have public IP address at home, I am using VPS with public IP address
- Alternative would be cloudflare tunnel (which works fine in most cases), but as long as it has some limitations and it is third party service I prefer to use VPS
- Best provider in Czech is [Hukot.net](https://www.hukot.net) for 140 Kč/month with unlimited traffic, 4 GB RAM, 40 GB SSD and 2 CPU Core.
- For connection between my homelab and VPS I am using Tailscale

## Hypervisor

- Proxmox

## Virtual machines

- Main - Debian - Main VM for most of the docker services
- Friend's backup - Debian - VM for backup data for my friend

## Containers

- All services use docker containers
- Server use container orchestration - Kubernetes

## Other

- Autosynchronization with github repository
- Autorestart per week

## Hosted services

- Cloud
  - [Nextcloud](https://nextcloud.com/) - cloud platform
- Gaming
  - [Minecraft server](https://docker-minecraft-server.readthedocs.io/en/latest/) - minecraft server
- Media
  - [Jellyfin](https://jellyfin.org/) - video streaming platform
  - [Radarr](https://radarr.video/) - media downloader
  - [Sonarr](https://sonarr.tv/) - media indexing
- Monitoring
  - [Grafana](https://grafana.com/) - data visualization
  - [Prometheus](https://prometheus.io/) - data collecting
- Network
  - [Nginx](https://nginx.com) - reverse proxy
  - [Pihole](https://pi-hole.net/) - local DNS and add blocker
- Photo managment
  - [Immich](https://immich.app/) - web gallery and mobile gallery backup
    - 🏁 Purpose - Web application for connecting mobile and camera media, viewing and sharing photos with multiuser support, photo synchronization, ai recognition, map and more.
    - 📍 Missing:
      - Specific folder sharing
    - ❔ Alternatives:
      - [Photoprism](https://www.photoprism.app/):
        - ✅ Pros - specific folder sharing
        - ❌ Cons - missing multiuser separate galleries, slower and "closed" develompent
  - [Piwigo](https://piwigo.org/) - photography portfolio
    - 🏁 Purpose - Web application for personal photography portfolio with functional API for web implentation.
    - 📍 Missing:
      - Following folder strucure, all photos have to be manually uploaded
      - Lack of modern design
    - ❔ Alternatives:
      - [Lychee](https://lycheeorg.github.io/):
        - ❌ Cons - different gallery concept
- Smart home
  - [Deconz](https://www.phoscon.de/en/conbee2/software) - zigbee deconz gateway
  - [Homeassistant](https://www.home-assistant.io/) - smarthome manager
- Statistics and analytics
  - [Plausible](https://plausible.io/) - alternative to google analytics
  - [Wakapi](https://wakapi.dev/) - coding statistics
  - [YourSpotify](https://github.com/Yooooomi/your_spotify) - spotify statistics
- Other
  - [Borgmatic](https://torsion.org/borgmatic/) - backup
  - [Code server](https://coder.com/) - web browser coding
  - [Discord Music Bot](https://github.com/SudhanPlayz/Discord-MusicBot) - discord music bot
  - [Free Games Claimer](https://github.com/vogler/free-games-claimer) - automatically collect free games
  - [Authentik](https://goauthentik.io/) - single authorization
  - [Ghost](https://ghost.org/) - blogging platform
  - [Homer](https://github.com/bastienwirtz/homer) - cloud homepage
  - [MagicMirror](https://magicmirror.builders/) - magic mirror server
  - [Mastodon](https://joinmastodon.org/) - social medium
  - [Rallly](https://rallly.co/) - event planning
  - [Reactive Resume](https://rxresu.me/) - resume web builder
  - [RSS Hub](https://docs.rsshub.app/) - rss network
  - [Tailscale](https://tailscale.com/) - for VPN and connection to VPS
  - [Vaultwarden](https://www.vaultwarden.net/) - password manager
  - [Watchtower](https://containrrr.dev/watchtower/) - docker images autoupdater
  - [Wordpress](https://wordpress.org/) - website builder
  - [Yourls](https://yourls.org/) - link shortener
