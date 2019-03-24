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
- Shairport (Airplay server on linux)
- mopidy (MPD server used for alarm clock)
- Plex (media server)
- Deluge (torrent)
- molnarjani/appdaemon-apps (app used to wake me up by gradually increasing lights and playing music louder)
- notesapp (custom note taking app, WIP)
- Octoprint (3D printing jobs)
- Theia (Web IDE)

Must have:
  - Proxmox (On a physical host, for running all vms) [Done]
  - Portainer (On a physical host, for running and managing Docker container) [Done]
  - Landing page to services
  - Guacamole (RDP, SSH, VNC access for all VMs)
 
Could be useful:
  - NAS, backups
  - Gitea (self-hosted git repos)
  - CI/CD pipline
  - Plex (Video streaming)
  - Pi-hole (Ad firewall)
  - OwnCloud
  - Codiad/Theia (cloud IDE)
  - TorrentBox
  - some music streamer
  - dev boxes/docker containers for breaking stuff
  - Wiki
  - Squid (caching proxy)

Ideas using the server:
  - Alarm clock:
    - A page/mobile app where i could add alarms and alarms would intetract with wifi controlled lightbulbs + play music to wake me up smoothly
  

Potential cool ideas:
https://github.com/Kickball/awesome-selfhosted
