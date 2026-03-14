# TryHackMe - Linux CLI Basics

## Introduction

The **Linux CLI** (Command Line Interface) is a text-based way to interact with a Linux operating system.  
Instead of using a graphical interface, commands are entered directly into a terminal.

Learning the Linux command line is essential in cybersecurity because many tools, systems, and servers are managed through the terminal.

---

## What is the CLI?

CLI stands for **Command Line Interface**.  
It allows the user to communicate with the system by typing commands.

This is especially useful for:

- navigating through directories
- creating, moving, copying, or deleting files
- reading file contents
- managing the system more efficiently

Example:

```bash
pwd
```

This command displays the **current working directory**.

---

## Basic Navigation Commands

### `pwd`

Displays the current path you are in.

```bash
pwd
```

Example output:

```bash
/home/user
```

---

### `ls`

Lists the contents of a directory.

```bash
ls
```

Useful options:

```bash
ls -l
```

Shows detailed information about files and directories.

```bash
ls -a
```

Displays hidden files as well.

---

### `cd`

Changes the current directory.

```bash
cd folder_name
```

Examples:

```bash
cd /home/user/Documents
cd ..
cd ~
```

Explanation:

- `cd ..` → move up one directory
- `cd ~` → return to the home directory

---

## File and Directory Management

### `mkdir`

Creates a new directory.

```bash
mkdir test_folder
```

---

### `touch`

Creates a new empty file.

```bash
touch notes.txt
```

---

### `cp`

Copies a file or directory.

```bash
cp file.txt backup.txt
```

To copy a directory recursively:

```bash
cp -r folder1 folder2
```

---

### `mv`

Moves or renames a file.

Rename a file:

```bash
mv oldname.txt newname.txt
```

Move a file to another directory:

```bash
mv notes.txt /home/user/Documents
```

---

### `rm`

Deletes a file.

```bash
rm file.txt
```

Delete a directory and its contents:

```bash
rm -r folder_name
```

> Be careful: deleted files are not easily recoverable.

---

## Reading File Contents

### `cat`

Displays the contents of a file.

```bash
cat file.txt
```

---

### `less`

Opens a file for easier reading, especially if it is long.

```bash
less file.txt
```

---

## Useful Terminal Shortcuts

| Shortcut | Function |
|----------|----------|
| Tab | Autocomplete commands and file names |
| ↑ | Recall the previous command |
| Ctrl + C | Stop the current command |
| Ctrl + L | Clear the terminal |

---

## Why Linux CLI Matters in Cybersecurity

Linux is everywhere in cybersecurity:

- servers often run Linux
- many pentesting tools are built for Linux
- security analysts often work in terminal environments
- automation and scripting rely heavily on command-line usage

Being comfortable with the Linux CLI is a basic but essential skill for anyone entering the cybersecurity field.

---

## Key Takeaways

- The CLI is a text-based way to interact with Linux.
- Commands like `pwd`, `ls`, and `cd` are essential for navigation.
- Commands like `mkdir`, `touch`, `cp`, `mv`, and `rm` are used to manage files and directories.
- Commands like `cat` and `less` are useful for reading files.
- Linux CLI skills are fundamental in cybersecurity.