# Networking basics #1

Working with localhost, 0.0.0.0, the `/etc/hosts` file, network interfaces and netcat.

## Tasks

| # | File | Description |
|---|------|-------------|
| 0 | `0-change_your_home_IP` | Configures the server so `localhost` resolves to `127.0.0.2` and `facebook.com` to `8.8.8.8` |
| 1 | `1-show_attached_IPs` | Displays all active IPv4 IPs on the machine |
| 2 | `2-port_listening_on_localhost` | Listens on port 98 on `localhost` |

## Usage

```bash
sudo ./0-change_your_home_IP
./1-show_attached_IPs
sudo ./2-port_listening_on_localhost   # then, in another terminal: telnet localhost 98
```

> If you run task 0 on a machine you keep using, revert `localhost` to `127.0.0.1` afterwards.

## Requirements

- Ubuntu 22.04
- Scripts are executable and pass Shellcheck (0.7.0)
- First line of every script: `#!/usr/bin/env bash`
- Second line: a comment explaining what the script does

## Author

Antonio Torres
