# Linux Notes

## Day 1

### pwd
Show current directory

```bash
pwd
```

### ls
List files and directories

```bash
ls
```

### touch
Create a file

```bash
touch app.log
```

### cat
Display file contents

```bash
cat app.log
```

### head
Show first lines

```bash
head app.log
```

### tail
Show last lines

```bash
tail app.log
```

### grep
Search text in a file

```bash
grep ERROR app.log
```

Output:

```
ERROR Timeout occurred
```
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
