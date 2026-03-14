# Vault Homelab

This repository contains the [Docker Compose](https://docs.docker.com/compose/) configuration files for **Vault**, a self-hosted homelab environment managed with containerized services. The setup is designed for reliability and flexibility, leveraging [Komodo](https://github.com/moghtech/komodo) for container management and [Backrest](https://github.com/garethgeorge/backrest) for backups.

This setup allows for centralized management of media, monitoring, backups, and productivity tools for home use.


![Vault Homelab Dashboard](./preview.png)


### 🖥️ System Specifications

- **OS:** Debian server ([debian:stable](https://www.debian.org/releases/stable/))
- **CPU:** 13th Gen Intel(R) Core(TM) i3-13100
- **RAM:** Corsair 8GB DDR4 @ 3200Mhz (Single Dimm)
- **Motherboard:** Gigabyte H610M H V2 DDR4
- **Network:** [Rocketnet](https://rocketnet.co.za/) 500mbps Upload/Download via [Metrofibre](https://metrofibre.co.za/)
- **Storage:** 
    - 1x 512GB Kimtigo NVME SSD
    - 2x 2TB Seagate HDD
    - 1x 4TB Western Digital HDD

---


### 📦 Core Services

Although I am constantly testing out new containers and services, below are the core services I will likely always be running:

- **[Backrest](https://github.com/garethgeorge/backrest)**: Backup management
- **[Homepage](https://github.com/gethomepage/homepage)**: Customizable dashboard
- **[Plex](https://plex.tv/)**: Media server for streaming
- **[QBittorrent](https://github.com/VueTorrent/VueTorrent)**: Download client
- **[Vaultwarden](https://github.com/dani-garcia/vaultwarden)**: Password manager

---



### 📜 License

The Vault Homelab is provided under the MIT license.