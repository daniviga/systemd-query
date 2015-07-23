## systemd-query

A small wrapper to simplify enabling and disabling systemd services.

### Installation:

- Download the script into a directory in system PATH (/usr/local/sbin/ is recommended)
- Make the script executable by root

```bash
wget -O- https://github.com/daniviga/systemd-query/blob/master/systemd-query | sudo tee /usr/local/sbin/systemd-query
sudo chmod +x /usr/local/sbin/systemd-query
```

### Usage:
- list [enabled | disabled | all]
- enable <service> | disable <service>
- start <service> | stop <service> | restart <service> | status <service>

### Requirements:
- systemd
- BASH >= 4.0
