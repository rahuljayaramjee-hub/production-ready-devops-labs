# Linux Log Management 📋

## Introduction
Logs help administrators monitor system activity, troubleshoot issues, and track application behavior.

---

## View System Logs

```bash
journalctl
```

---

## View Recent Logs

```bash
journalctl -n 20
```

---

## Follow Logs in Real Time

```bash
journalctl -f
```

---

## View Logs for a Service

```bash
journalctl -u nginx
```

---

## View Traditional Log Files

```bash
ls /var/log
```

Example:

```bash
cat /var/log/syslog
```

---

## Search Logs for Errors

```bash
grep "error" /var/log/syslog
```

---

## Conclusion

Log management is essential for troubleshooting servers, monitoring applications, and maintaining Linux systems.

---

# Linux System Logs

System logs are files that store information about system events, applications, errors, and user activities. Logs help administrators monitor system health and troubleshoot issues.

## Common Log Locations

- `/var/log/syslog` – General system logs
- `/var/log/auth.log` – Authentication logs
- `/var/log/kern.log` – Kernel logs

## Useful Commands

- `cat` – View log files
- `tail -f` – Monitor logs in real time
- `grep` – Search for specific entries

## Benefits

- Troubleshoot errors
- Monitor system activity
- Track security events
- Improve system reliability

Understanding Linux logs is an important skill for DevOps and Cloud Engineers because logs provide insights into system behavior and performance.
