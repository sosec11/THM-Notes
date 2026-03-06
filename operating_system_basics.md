# TryHackMe — Operating System Basics

## Overview

This room introduces the role of an **Operating System (OS)** and explains how it manages hardware and software resources. The OS acts as an intermediary between the user, applications, and the computer hardware.

Understanding how operating systems work is essential in cybersecurity because most security controls, processes, and attacks interact directly with the OS.

---

# What is an Operating System?

An **Operating System (OS)** is software that manages a computer's hardware and provides services for applications.

Common operating systems include:

- Windows
- Linux
- macOS
- Android
- iOS

The OS ensures that programs can run and interact properly with hardware components.

---

# Core Responsibilities of an Operating System

## Process Management

The OS manages **processes**, which are programs currently running on the system.

Responsibilities include:

- Creating processes
- Scheduling CPU time
- Managing multiple processes simultaneously

This allows **multitasking**, where several applications run at the same time.

---

## Memory Management

The operating system manages **RAM allocation** for running programs.

Tasks include:

- Assigning memory to processes
- Preventing programs from interfering with each other
- Managing virtual memory when RAM is limited

Proper memory management is critical for **system stability and security**.

---

## File System Management

The OS organizes and manages files stored on disk.

Functions include:

- Creating files and directories
- Reading and writing data
- Managing permissions and access control

Different operating systems use different file systems (for example: **NTFS**, **ext4**).

---

## Device Management

The OS communicates with hardware devices through **drivers**.

Examples of managed devices:

- Keyboard
- Mouse
- Network card
- Storage devices
- Printers

Drivers allow the OS to control and communicate with hardware components.

---

# User Interaction with the OS

Users interact with an operating system through two main interfaces.

## Graphical User Interface (GUI)

A visual interface with windows, icons, and menus.

Examples:

- Windows desktop
- macOS interface
- Linux desktop environments

This interface is easier for everyday users.

---

## Command Line Interface (CLI)

A text-based interface where users type commands.

Examples:

- Bash (Linux)
- PowerShell (Windows)
- Terminal

The CLI is widely used in **system administration and cybersecurity** because it allows precise control over the system.

---

# Why Operating Systems Matter in Cybersecurity

Security professionals interact constantly with operating systems because:

- Malware runs as processes inside the OS
- Permissions control access to sensitive files
- System logs help investigate incidents
- Many vulnerabilities exist in OS services

Understanding the OS helps analysts:

- detect suspicious activity
- analyze compromised systems
- perform forensic investigations

---

# Key Concepts Learned

- Role of an Operating System
- Process management
- Memory management
- File systems
- Device drivers
- GUI vs CLI interaction

---

# Progress Log

Room completed as part of my cybersecurity learning path on TryHackMe.