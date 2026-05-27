# Linux Process Management ⚙️

## Introduction
Linux processes are running programs or services inside the operating system. Process management commands help monitor and control system tasks.

---

## View Running Processes

```bash
ps aux
```

This displays all running processes in the system.

---

## Real-Time Process Monitoring

```bash
top
```

Shows CPU usage, memory usage, and active processes in real time.

---

## Kill a Process

```bash
kill <PID>
```

Example:

```bash
kill 1234
```

---

## Force Stop a Process

```bash
kill -9 <PID>
```

---

## Find Process ID

```bash
pidof nginx
```

This returns the process ID of nginx service.

---

## Conclusion
Process management is an important Linux administration skill used in servers, DevOps, and troubleshooting environments.