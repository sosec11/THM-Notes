# TryHackMe - Windows CLI Basics

## Introduction

The **Windows Command Line Interface (CLI)** allows users to interact with the Windows operating system using text commands instead of the graphical interface.

Two main command-line environments exist in Windows:

- **Command Prompt (cmd.exe)**
- **PowerShell**

Understanding how to use the Windows CLI is important for **system administration, troubleshooting, and cybersecurity**, since many administrative and security tasks can be performed through the terminal.

---

## What is the Windows CLI?

The **Command Line Interface (CLI)** allows users to communicate with the operating system by typing commands.

Instead of navigating through menus and windows, commands are executed directly in the terminal.

This allows users to:

- navigate through directories
- manage files and folders
- inspect system information
- automate tasks

Example command:

```cmd
cd
```

This command displays the **current working directory**.

---

## Basic Navigation Commands

### `dir`

Lists the contents of a directory.

```cmd
dir
```

This command displays:

- files
- folders
- file sizes
- modification dates

---

### `cd`

Changes the current directory.

```cmd
cd folder_name
```

Examples:

```cmd
cd Documents
cd ..
cd \
```

Explanation:

- `cd ..` → move up one directory
- `cd \` → return to the root directory

---

### `cls`

Clears the terminal screen.

```cmd
cls
```

This helps keep the terminal readable when many commands have been executed.

---

## File and Directory Management

### `mkdir`

Creates a new directory.

```cmd
mkdir test_folder
```

---

### `rmdir`

Removes a directory.

```cmd
rmdir folder_name
```

To remove a directory and its contents:

```cmd
rmdir /s folder_name
```

---

### `copy`

Copies files from one location to another.

```cmd
copy file.txt backup.txt
```

---

### `move`

Moves files from one location to another.

```cmd
move file.txt Documents\
```

---

### `del`

Deletes a file.

```cmd
del file.txt
```

Be cautious when deleting files, as they are not easily recoverable from the command line.

---

## Viewing File Contents

### `type`

Displays the contents of a file directly in the terminal.

```cmd
type file.txt
```

This is useful for quickly reading small text files.

---

## Useful Terminal Shortcuts

| Shortcut | Function |
|----------|----------|
| ↑ | Show the previous command |
| Tab | Autocomplete file and folder names |
| Ctrl + C | Stop the current command |
| Ctrl + L | Clear the screen (in some environments) |

---

## Why Windows CLI Matters in Cybersecurity

Although Linux is heavily used in cybersecurity, Windows systems are extremely common in corporate environments.

Security professionals often use the Windows CLI to:

- analyze system configurations
- investigate files and directories
- manage user accounts
- troubleshoot systems
- run administrative commands

Understanding the Windows CLI is therefore essential for **incident response, system administration, and penetration testing**.

---

## Key Takeaways

- Windows provides command-line tools such as **Command Prompt** and **PowerShell**.
- Commands like `dir`, `cd`, and `cls` help navigate and manage the system.
- Commands like `copy`, `move`, and `del` allow file management.
- The CLI provides a fast and efficient way to interact with the system.
- Windows CLI knowledge is important for cybersecurity professionals.

---

## Conclusion

The **Windows CLI Basics** module introduces the essential commands used to interact with the Windows command line.

These commands form the foundation for more advanced administrative and cybersecurity tasks in Windows environments.