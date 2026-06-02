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
