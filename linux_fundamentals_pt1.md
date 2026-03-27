# TryHackMe - Linux Fundamentals Part 1

## Introduction

Linux is an open-source operating system widely used in servers, cybersecurity, and development environments.

This module introduces the basics of Linux, including:

- file system structure
- navigation commands
- working with files
- basic terminal usage

Understanding Linux is essential for cybersecurity professionals, as many tools and systems rely on it.

---

## What is Linux?

Linux is an operating system similar to Windows but with a strong focus on:

- flexibility
- security
- command-line usage

It is commonly used in:

- servers
- cloud environments
- penetration testing (e.g., Kali Linux)

---

## The Linux File System

Linux uses a hierarchical file system starting from the root directory:

```
/
```

Common directories include:

- `/home` → user directories
- `/etc` → configuration files
- `/var` → logs and variable data
- `/bin` → essential binaries (commands)

---

## Basic Navigation Commands

### `pwd`

Displays the current directory.

```bash
pwd
```

---

### `ls`

Lists files and directories.

```bash
ls
```

Options:

```bash
ls -l
ls -a
```

---

### `cd`

Changes directory.

```bash
cd folder_name
```

Examples:

```bash
cd /home/user
cd ..
cd ~
```

---

## Working with Files

### Viewing Files

```bash
cat file.txt
```

---

### Creating Files

```bash
touch file.txt
```

---

### Creating Directories

```bash
mkdir new_folder
```

---

### Removing Files

```bash
rm file.txt
```

Remove directories:

```bash
rm -r folder_name
```

---

## Searching for Files

### `find`

Used to search for files in the system.

```bash
find / -name file.txt
```

---

### `grep`

Searches for text within files.

```bash
grep "text" file.txt
```

---

## File Permissions

Linux controls access to files using permissions:

- read (r)
- write (w)
- execute (x)

Permissions apply to:

- owner
- group
- others

Example:

```bash
ls -l
```

Displays file permissions.

---

## Why Linux Matters in Cybersecurity

Linux is heavily used in cybersecurity because:

- many servers run Linux
- most security tools are designed for Linux
- penetration testing environments rely on Linux
- scripting and automation are commonly done in Linux

Understanding Linux is a fundamental skill for any cybersecurity professional.

---

## Key Takeaways

- Linux is a widely used operating system in cybersecurity.
- The file system starts at the root (`/`).
- Commands like `ls`, `cd`, and `pwd` are essential.
- File management and permissions are key concepts.
- Tools like `find` and `grep` help search files and data.

---

## Conclusion

The **Linux Fundamentals Part 1** module introduces the core concepts of working with a Linux system.

Mastering these basics is essential for progressing in cybersecurity and system administration.