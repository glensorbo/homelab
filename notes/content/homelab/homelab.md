---
id: 1746178822-SXUX
aliases:
  - homelab
tags: []
---

# Homelab

My homelab servers and applications needs a bit of an overhaul. I'm going to utilize [coolify](https://coolify.io/docs/get-started/installation) to manage all my apps.

## TrueNAS

- Needs semi-good hardware
- Needs 2.5gbe Intel based NIC as TrueNAS have problems with realtek chips
- Needs a minimum 2 x 4T hdds for cold storage and x size m.2 cache drive. Also an SSD for OS.
- Will run Nextcloud and all file upload/download will go through NC

## Proxmox

- Needs good hardware
- Needs 2.5gbe NIC. Intel based NIC would be nice here as well
- Needs disks, not sure which yet

### Proxmox servers

- Coolify manager (host coolify dashboard etc)
- Coolify server (host applications)

## AI and game server

- Needs GPU for AI
- Needs CPU WITHOUT graphics as it has been a struggle for AI software
- Needs OS drive - no need to big storage as backups will be sent to TrueNAS and locally deleted afterwards
