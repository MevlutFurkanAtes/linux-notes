
## Day 2 - System Monitoring

### free -h
Display memory usage.

```bash
free -h
```

---

### df -h
Display disk usage.

```bash
df -h
```

---

### systemctl status ssh
Check SSH service status.

```bash
systemctl status ssh
```

---

### journalctl -u ssh
Display SSH logs.

```bash
journalctl -u ssh
```

Exit:

```
q
```
# Bash Scripts

Basic Bash scripts for Linux system administration.

## service_check.sh

Checks disk usage, memory usage and SSH service status.

```bash
#!/bin/bash

echo "===== Disk Usage ====="
df -h

echo ""

echo "===== Memory Usage ====="
free -h

echo ""

echo "===== SSH Service Status ====="
systemctl status ssh --no-pager
```

### Usage

Make executable:

```bash
chmod +x service_check.sh
```

Run:

```bash
./service_check.sh
```

### Features

* Display disk usage
* Display memory usage
* Check SSH service status

### Technologies

* Linux
* Bash
* System Administration
* Service Monitoring
