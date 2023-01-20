<p align="right"><a href="https://github.com/hostlikepro/proxmox-scripts/blob/main/UptimeKuma-LXC/readme.md"><b>RU version</b></a></p>

# Uptime Kuma LXC
Uptime Kuma is a self-hosted, open source, fancy uptime monitoring and alerting system. It can monitor HTTP(s) / TCP / HTTP(s) Keyword / Ping / DNS Record / Push / Steam Game Server.

---

## Installation
To create a new Proxmox Uptime Kuma LXC, run the command below in the Proxmox Shell.
To Update Uptime Kuma, run the command below in the LXC Console.
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/hostlikepro/proxmox-scripts/main/UptimeKuma-LXC/setup.sh)"
```
To setup Uptime Kuma in an already created LXC or in another kind of container, run this command in the LXC Console.
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/hostlikepro/proxmox-scripts/main/UptimeKuma-LXC/install.sh)"
```
> **Note:** _not recommended._

---

## Default Settings 
System requirements - 1GiB RAM / 2GiB Storage / 1vCPU

Uptime-Kuma WebUI: http://127.0.0.1:3001
> **Note:** _tested at Proxmox v.7+._

---