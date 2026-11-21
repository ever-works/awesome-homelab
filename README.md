# Awesome Homelab

A curated directory of homelab hardware, hypervisors, self-hosted software, networking and guides.

## 📑 Table of Contents

- [Guides & Communities (3)](#guides--communities)
- [Hardware (Mini PCs, NAS, Networking) (4)](#hardware-mini-pcs-nas-networking)
- [Hypervisors & Operating Systems (4)](#hypervisors--operating-systems)
- [Monitoring & Dashboards (2)](#monitoring--dashboards)
- [Networking & VPN (4)](#networking--vpn)
- [Self-Hosted Apps (6)](#self-hosted-apps)


## Guides & Communities

- [r/homelab](https://www.reddit.com/r/homelab) - Reddit community dedicated to homelab discussions. Users share hardware builds, software configurations, and troubleshooting advice. Free to read and participate. ([Read more](/details/r-homelab.md)) `Free` `Community` `Forum` `Guides` `Homelab`
- [ServeTheHome](https://servethehome.com/) - Independent technology news and review site focused on servers and storage. Publishes hardware reviews, guides, and homelab content. Free access. ([Read more](/details/servethehome.md)) `Free` `Community` `Guides` `Reviews` `Hardware`
- [Techno Tim](https://technotim.live/) - Content creator and homelab enthusiast. Publishes tutorials, hardware reviews, and software guides for self-hosting. Free access to articles and videos. ([Read more](/details/techno-tim.md)) `Free` `Community` `Guides` `Tutorials` `Homelab`

## Hardware (Mini PCs, NAS, Networking)

- [QNAP QTS](https://www.qnap.com/) - Operating system for QNAP NAS appliances. Supports storage, virtualization, containerization, and multimedia applications. Licensed with hardware purchase. ([Read more](/details/qnap-qts.md)) `Paid` `Hardware` `NAS` `Storage` `Self-Hosted`
- [Raspberry Pi](https://www.raspberrypi.com/) - Series of small single-board computers. Widely used in homelabs for lightweight servers, media centers, and IoT projects. Sold as commercial hardware. ([Read more](/details/raspberry-pi.md)) `Paid` `Hardware` `Mini PC` `Single Board Computer` `IoT`
- [Synology DSM](https://www.synology.com/) - Linux-based operating system for Synology NAS devices. Provides file sharing, backup, surveillance, and package management. Bundled with Synology hardware. ([Read more](/details/synology-dsm.md)) `Paid` `Hardware` `NAS` `Storage` `Self-Hosted`
- [Ubiquiti UniFi](https://ui.com/) - Commercial networking hardware and software ecosystem. Includes access points, switches, gateways, and a centralized controller. Managed via UniFi Network application. ([Read more](/details/ubiquiti-unifi.md)) `Paid` `Hardware` `Networking` `Wi-Fi` `Controller`

## Hypervisors & Operating Systems

- [Proxmox VE](https://www.proxmox.com/en) - Open-source virtualization platform based on Debian. Supports KVM virtual machines and LXC containers with a web-based management interface. Used for home labs and enterprise virtualization. ([Read more](/details/proxmox-ve.md)) `Open Source` `Self-Hosted` `Hypervisor` `Virtualization` `API`
- [TrueNAS](https://www.truenas.com/) - Network-attached storage operating system based on OpenZFS. Provides storage management, replication, and sharing via SMB, NFS, and iSCSI. Developed by iXsystems. ([Read more](/details/truenas.md)) `Open Source` `Self-Hosted` `NAS` `ZFS` `Storage`
- [Ubuntu Server](https://ubuntu.com/server) - Linux server distribution by Canonical. Optimized for cloud, data center, and homelab deployments with LTS releases. Free to use with optional paid support. ([Read more](/details/ubuntu-server.md)) `Open Source` `Self-Hosted` `Linux` `Server` `Cloud`
- [Unraid](https://unraid.net/) - Proprietary NAS and virtualization operating system. Uses a unique array design allowing mixed drive sizes and includes Docker and VM support. Licensed per server. ([Read more](/details/unraid.md)) `Paid` `Self-Hosted` `NAS` `Virtualization` `Docker`

## Monitoring & Dashboards

- [Grafana](https://grafana.com/) - Open-source analytics and monitoring platform. Queries, visualizes, and alerts on metrics from multiple data sources. Offers self-hosted and cloud options. ([Read more](/details/grafana.md)) `Open Source` `Self-Hosted` `Monitoring` `Dashboards` `API`
- [Uptime Kuma](https://uptime.kuma.pet/) - Self-hosted monitoring tool for tracking website and service uptime. Supports HTTP, TCP, and DNS monitoring with notifications. Open-source with a web dashboard. ([Read more](/details/uptime-kuma.md)) `Open Source` `Self-Hosted` `Monitoring` `Uptime` `Dashboard`

## Networking & VPN

- [OPNsense](https://opnsense.org/) - Open-source firewall and routing distribution based on FreeBSD. Offers web GUI, intrusion detection, and VPN capabilities. Suitable for replacing consumer routers. ([Read more](/details/opnsense.md)) `Open Source` `Self-Hosted` `Firewall` `Router` `FreeBSD`
- [pfSense](https://www.pfsense.org/) - Open-source firewall and router software based on FreeBSD. Provides packet filtering, VPN, and traffic shaping through a web interface. Maintained by Netgate. ([Read more](/details/pfsense.md)) `Open Source` `Self-Hosted` `Firewall` `Router` `FreeBSD`
- [Tailscale](https://tailscale.com/) - Zero-config VPN built on WireGuard. Creates private networks between devices using existing identity providers. Offers free personal plans and paid business tiers. ([Read more](/details/tailscale.md)) `Freemium` `Self-Hosted` `VPN` `WireGuard` `API`
- [WireGuard](https://www.wireguard.com/) - Open-source VPN protocol and software. Designed for simplicity and high performance with modern cryptography. Can be self-hosted or integrated into other tools. ([Read more](/details/wireguard.md)) `Open Source` `Self-Hosted` `VPN` `Protocol` `API`

## Self-Hosted Apps

- [Docker](https://www.docker.com/) - Containerization platform for developing, shipping, and running applications. Uses OS-level virtualization to deliver software in containers. Community edition is free; Docker Desktop has paid terms for large enterprises. ([Read more](/details/docker.md)) `Open Source` `Self-Hosted` `Containers` `API` `Linux`
- [Home Assistant](https://www.home-assistant.io/) - Open-source home automation platform. Integrates with thousands of devices and services for local control and automation. Self-hosted on Raspberry Pi or servers. ([Read more](/details/home-assistant.md)) `Open Source` `Self-Hosted` `Home Automation` `IoT` `API`
- [Homepage](https://gethomepage.dev/) - Open-source dashboard for homelab services. Displays service status, widgets, and links in a customizable interface. Self-hosted via Docker. ([Read more](/details/homepage.md)) `Open Source` `Self-Hosted` `Dashboard` `Homelab` `Docker`
- [Nextcloud](https://nextcloud.com/) - Open-source self-hosted collaboration platform. Provides file storage, calendar, contacts, and document editing. Can be installed on private servers. ([Read more](/details/nextcloud.md)) `Open Source` `Self-Hosted` `File Storage` `Collaboration` `API`
- [Pi-hole](https://pi-hole.net/) - Network-level advertisement and tracker blocking sinkhole. Acts as a DNS sinkhole to block ads across all devices on a network. Open-source and self-hosted. ([Read more](/details/pi-hole.md)) `Open Source` `Self-Hosted` `DNS` `Ad Blocking` `Network`
- [Portainer](https://www.portainer.io/) - Container management UI for Docker and Kubernetes. Simplifies container, image, network, and volume administration. Offers community and business editions. ([Read more](/details/portainer.md)) `Freemium` `Self-Hosted` `Containers` `Docker` `Kubernetes` `Open Source`


## ™️ Legal

All product names, logos, and brands are the property of their respective owners. All company, product, and service names used in this repository, related repositories, and associated websites are for identification purposes only. The use of these names, logos, and brands does not imply endorsement, affiliation, or sponsorship.

This work may include content generated by artificial intelligence (AI). While efforts have been made to ensure the accuracy and reliability of the information, we make no representations or warranties of any kind, express or implied, about the completeness, accuracy, reliability, suitability, or availability of the information contained herein. Users are advised to independently verify the information before making decisions based on it.

We disclaim any responsibility for errors, omissions, or inaccuracies in the content, whether generated by humans, AI, or any other means. By using this work, you agree to use it at your own risk and acknowledge that the information provided may not always be current or accurate.

If you believe that your intellectual property rights or other legal rights have been infringed, please contact us immediately at legal@ever.co and we will take appropriate action.

## 🛡️ License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a

[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/

[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png

[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg