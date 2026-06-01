# Linux SSH Basics 🔐

## Introduction
SSH (Secure Shell) is used to securely connect to remote Linux servers over a network.

---

## Connect to a Remote Server

```bash
ssh username@server-ip
```

Example:

```bash
ssh ubuntu@192.168.1.10
```

---

## Check SSH Service Status

```bash
sudo systemctl status ssh
```

---

## Generate SSH Key Pair

```bash
ssh-keygen
```

---

## Copy SSH Key to Server

```bash
ssh-copy-id username@server-ip
```

---

## Exit SSH Session

```bash
exit
```

---

## Conclusion

SSH is one of the most important tools for Linux administration, cloud servers, and DevOps operations.
