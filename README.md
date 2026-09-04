# firewall-helper-cli (`frwll`)

A lightweight, universal CLI firewall management tool for Linux systems running `firewalld`, `ufw`, or `iptables`.

## Features

- **Backend Agnostic:** Automatically detects active firewall engines (`firewalld`, `ufw`, `iptables`).
- **Input Validation:** Strict parsing for port numbers (1-65535) and protocols (`tcp`/`udp`).
- **Safe Execution:** Pre-checks execution context (`root`/`sudo`) and syntax errors before applying rules.
- **Port Querying:** Easily inspect specific port states or list all open ports uniformly.

## Installation

```bash
sudo cp frwll /usr/local/bin/
sudo chmod +x /usr/local/bin/frwll
