# Linux Service Management 🔧

## Introduction
Services are background processes that run automatically in Linux. The `systemctl` command is used to manage services.

---

## Check Service Status

```bash
systemctl status nginx
```

---

## Start a Service

```bash
sudo systemctl start nginx
```

---

## Stop a Service

```bash
sudo systemctl stop nginx
```

---

## Restart a Service

```bash
sudo systemctl restart nginx
```

---

## Enable Service at Boot

```bash
sudo systemctl enable nginx
```

---

## List Running Services

```bash
systemctl --type=service --state=running
```

---

## Conclusion

Service management is an essential Linux skill used for managing web servers, databases, and applications in DevOps environments.
