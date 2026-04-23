# Homelab Network Dashboard

An interactive network topology and service status dashboard for a production-style homelab. Visualizes VLAN segmentation, Docker service health, and infrastructure topology in a single-page web application.

**Live demo:** Deploy via GitHub Pages (Settings > Pages > Source: main)

## Features

- Interactive network topology visualization showing all VLANs, devices, and connections
- Real-time service status indicators for all Docker containers
- VLAN segmentation overview with subnet details and firewall policies
- Hardware specs and VM resource allocation
- Storage architecture breakdown (NVMe + HDD tiered layout)
- Responsive dark theme matching the homelab portfolio aesthetic

## Stack

Single-file static HTML with vanilla JavaScript and CSS. No build tools, no frameworks, no API calls. All data is hardcoded to match the current infrastructure state — update the data objects in the HTML to reflect changes.

## About

Part of a larger homelab project: [github.com/gavin-michael/HomeLab-Server](https://github.com/gavin-michael/HomeLab-Server)

Built by [Gavin White](https://gavinwhite.dev) — CompTIA Security+ certified, studying for CCNA.
