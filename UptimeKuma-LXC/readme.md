<p align="right"><a href="https://github.com/hostlikepro/proxmox-scripts/blob/main/UptimeKuma-LXC/readme_eng.md"><b>ENG version</b></a></p>

# Uptime Kuma LXC
Uptime Kuma — это автономная система мониторинга и оповещения с открытым исходным кодом. Она включает возможность отслеживания работоспособности протоколов: HTTP(s) / TCP / HTTP(s) / Ping / DNS Record / Push / Steam Game Server.

---

## Установка
Чтобы создать новый Proxmox Uptime Kuma LXC контейнер, выполните приведенную ниже команду в Proxmox Shell.
Для обновления Uptime Kuma, воспользуйтесь этой же командной, но в консоли необходимого LXC контейнера.
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/hostlikepro/proxmox-scripts/main/UptimeKuma-LXC/setup.sh)"
```
Для установки Uptime Kuma на уже созданный ранее LXC контейнер, либо в другие системы контейнеризации, воспользуйтесь командой ниже.
> **Примечание:** _не рекомендуется._
```
bash -c "$(wget -qLO - https://raw.githubusercontent.com/hostlikepro/proxmox-scripts/main/UptimeKuma-LXC/install.sh)"
```

---

## Параметры
Системные требования - 1GiB RAM / 2GiB Storage / 1vCPU

Uptime-Kuma WebUI: http://127.0.0.1:3001
> **Примечание:** _тестировалось на Proxmox v.7+._

---


