# Networking basics #0

Introduction to networking: the OSI model, network types, MAC and IP addresses, TCP vs UDP, ports, and basic diagnostic tools.

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-OSI_model` | Questions on the OSI model |
| 1 | `1-types_of_network` | Questions on LAN, WAN and the Internet |
| 2 | `2-MAC_and_IP_address` | Questions on MAC and IP addresses |
| 3 | `3-UDP_and_TCP` | Questions on TCP and UDP |
| 4 | `4-TCP_and_UDP_ports` | Bash script that shows listening sockets with PID and program name (`netstat -lp`) |
| 5 | `5-is_the_host_on_the_network` | Bash script that pings an IP address 5 times; prints usage if no argument is given |

## Usage

```bash
./4-TCP_and_UDP_ports
./5-is_the_host_on_the_network 8.8.8.8
```

## Requirements

- Ubuntu 20.04 LTS
- Scripts are executable and pass Shellcheck
- First line of every script: `#!/usr/bin/env bash`
- Second line: a comment explaining what the script does

## Author

Antonio Torres
