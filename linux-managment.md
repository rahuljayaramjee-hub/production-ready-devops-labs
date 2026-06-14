# Linux User Management 👤

## Introduction
Linux user management is used to create, modify, and manage users in a system. It is important for server administration and security.

---

## Create New User

```bash
sudo useradd rahul
```

---

## Set User Password

```bash
sudo passwd rahul
```

---

## Switch User

```bash
su rahul
```

---

## View Current User

```bash
whoami
```

---

## Delete User

```bash
sudo userdel rahul
```

---

## View All Users

```bash
cat /etc/passwd
```

---

this is at the producation level


# Linux User Management

Linux user management is the process of creating, modifying, and managing user accounts on a system. Each user has a unique username and user ID (UID) that helps the operating system identify them.

User management is important for security because it controls who can access files, applications, and system resources.

## Common Commands

- `useradd` – Create a new user
- `passwd` – Set or change a password
- `usermod` – Modify a user account
- `userdel` – Delete a user account

## Benefits

- Improves system security
- Controls access to resources
- Supports multi-user environments
- Simplifies administration

Linux user management is a fundamental skill for system administrators, Cloud Engineers, and DevOps professionals.
