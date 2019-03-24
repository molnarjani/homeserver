# homeserver
Home Server project

What this is?
- My home server project ideas
- Some install instructions in case I forget them, possibly config files

# Current setup:

## Infra
- Proxmox (Debian base)
- Docker
- Portainer (Managing docker)
- watchtower (Autoupgrades docker containers, pulls new images periodically)

## Home Automation
- HomeAssistant (Home automation for smart lights and MPD)
- AppDaemon (Python services for HomeAssistant, used for alarmclock currently)

## Fun
- Heimdal (Dashboard app)
- Shairport (Airplay server on linux, git@github.com:abrasive/shairport.git, maybe shairport-sync is more maintained)
- mopidy (MPD server used for alarm clock)
- Plex (media server)
- Deluge (torrent)
- molnarjani/appdaemon-apps (app used to wake me up by gradually increasing lights and playing music louder)
- notesapp (custom note taking app, WIP)
- Octoprint (3D printing jobs)
- Theia (Web IDE)

# Stuff to add
  - Guacamole (RDP, SSH, VNC access for all VMs)
  - NAS, backups
  - Gitea (self-hosted git repos)
  - CI/CD pipline
  - Pi-hole (Ad firewall)
  - OwnCloud
  - Wiki
  - Squid (caching proxy)

Potential cool ideas:
https://github.com/Kickball/awesome-selfhosted
