# 100 Days of Homelab

Today 2022-07-11 I am starting the [#100DaysOfHomeLab](https://100daysofhomelab.com/)[^1] challenge.

[^1](https://docs.technotim.live/posts/100-days-of-homelab/)

## Introduction and Goals

My plan is to use the 100 days of homelab to organize and extend on my homelab as well as some home automation.

- proper network setup
    - central switch and WLAN
    - VLAN setup to limit smart home connections to the outside
- software stack rework
    - consider replacing proxmox with truenas scale
    - move HA addons to independant instances
        - bitwarden
        - tailscale
        - influxDB
        - graphana
- backups
    - verify and extend backup strategy
    - local backup of everthing
    - automatic remote backups
- heating automation
- UPS / battery powered server/lab

## Current (Active) Inventory

- proxmox server - **rocky**
    - Proxmox 7.2
    - 4 x Intel(R) Celeron(R) J4105 CPU @ 1.50GHz
    - 32GB RAM
    - 200GB SSD
    - mounted to wood panel

- VMs / Containers
    - `hass2` - Home Assistant 2022.7
    - `next` - Nextclound *inactive*
    - `camstore` - ftpd *inactive*

- Accessories
    - 1Gb Cable Internet (NAT)
    - Buffalo / ddWRT Router/Switch for LAN extension
    - 2x Reolink RLC-510A

## Interruptions
Having two small children I am expecting this challenge to be interrupted quite requlary.
Here I will track interruptions of my experiments and work that exceed my screensaver schedule only.
As ohterwise this section would quickly be dwarfing the rest of the text ;).

```
IIII
```
