8# Linux Disk Usage Commands 💾

## Introduction
Linux provides commands to check disk space and storage usage. These commands are useful for server monitoring and system administration.

---

## Check Disk Space

```bash
df -h
```

- `df` → Displays filesystem disk space
- `-h` → Human readable format

---

## Check Folder Size

```bash
du -sh Downloads/
```

- du → Disk usage
- -s → Summary
- -h → Human readable

---


## View Mounted Disks

```bash
lsblk
```

This shows storage devices and partitions.

---

## Conclusion
Disk management commands are important for Linux administration, troubleshooting, and DevOps operations


---


# Linux File System

The Linux file system organizes files and directories in a hierarchical structure starting from the root directory (`/`).

Common directories include `/home`, `/etc`, `/var`, and `/tmp`, each serving a specific purpose in the operating system.
