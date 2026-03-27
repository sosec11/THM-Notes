# Linux Command Cheat Sheet

## Introduction

This cheat sheet provides a quick reference to essential Linux commands commonly used in system administration and cybersecurity.

It is designed to help quickly recall commands and improve efficiency when working in a Linux environment.

---

## Navigation

```bash
pwd            # show current directory
ls             # list files
ls -l          # detailed list
ls -a          # show hidden files
cd folder      # enter directory
cd ..          # go up one level
cd ~           # go to home directory
```

---

## File Management

```bash
touch file.txt         # create file
mkdir folder           # create directory
cp file.txt copy.txt   # copy file
mv file.txt new.txt    # rename/move file
rm file.txt            # delete file
rm -r folder           # delete directory
```

---

## File Viewing

```bash
cat file.txt     # display content
less file.txt    # scroll through file
head file.txt    # first lines
tail file.txt    # last lines
```

---

## Searching

```bash
find / -name file.txt        # find file
grep "text" file.txt         # search text in file
grep -r "text" .             # search recursively
```

---

## Permissions

```bash
ls -l               # view permissions
chmod +x file       # make executable
chmod 755 file      # set permissions
chown user file     # change owner
```

---

## System Information

```bash
whoami        # current user
id            # user info
uname -a      # system info
top           # running processes
ps aux        # process list
```

---

## Networking

```bash
ip a              # show IP address
ping google.com   # test connectivity
netstat -tuln     # listening ports
ss -tuln          # alternative to netstat
```

---

## Package Management (Debian/Ubuntu)

```bash
sudo apt update
sudo apt upgrade
sudo apt install package
```

---

## Useful Shortcuts

| Shortcut | Action |
|----------|--------|
| Tab | Autocomplete |
| ↑ | Previous command |
| Ctrl + C | Stop command |
| Ctrl + L | Clear terminal |

---

## Why This Matters in Cybersecurity

Linux commands are used daily in cybersecurity for:

- navigating systems
- analyzing logs
- running security tools
- investigating incidents
- performing penetration testing

Being fast and comfortable with the CLI is a key skill for any cybersecurity professional.

---

## Key Takeaways

- Mastering basic commands improves efficiency.
- Linux CLI is essential in cybersecurity.
- Practice regularly to memorize commands.
- Use this cheat sheet as a quick reference.

---

## Conclusion

This cheat sheet provides a practical overview of essential Linux commands.

It is a useful resource for beginners and a quick reminder for more advanced users.