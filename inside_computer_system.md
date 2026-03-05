# TryHackMe — Inside a Computer System

## Overview
This room introduces the fundamental components of a computer system and explains how hardware and software interact to execute tasks. Understanding these concepts is essential for cybersecurity because every attack or defense ultimately interacts with these components.

---

# Main Components of a Computer

## 1. CPU (Central Processing Unit)
The CPU is the **brain of the computer**. It executes instructions from programs and performs calculations.

Main responsibilities:
- Execute instructions
- Process data
- Control other components

The CPU works through a cycle called the **Fetch–Decode–Execute cycle**:

1. Fetch → retrieve an instruction from memory  
2. Decode → understand what the instruction means  
3. Execute → perform the instruction  

---

## 2. Memory (RAM)
RAM (Random Access Memory) stores **temporary data** that the CPU needs while programs are running.

Characteristics:
- Fast access
- Temporary (data disappears when the computer shuts down)

Examples of what RAM stores:
- Running applications
- Active processes
- Temporary program data

---

## 3. Storage
Storage keeps **long-term data**.

Examples:
- Hard Disk Drive (HDD)
- Solid State Drive (SSD)

Storage contains:
- Operating system
- Installed programs
- Files and documents

When a program is launched:
1. It is loaded from **storage**
2. Into **RAM**
3. Then processed by the **CPU**

---

## 4. Input Devices
Input devices allow users to **send data to the computer**.

Examples:
- Keyboard
- Mouse
- Microphone
- Webcam

These devices convert human actions into signals that the computer can process.

---

## 5. Output Devices
Output devices allow the computer to **communicate results to the user**.

Examples:
- Monitor
- Speakers
- Printer

They convert digital signals into information humans can perceive.

---

# How Everything Works Together

A simplified workflow:

1. The user provides input (keyboard, mouse)
2. The data is loaded from storage to RAM
3. The CPU processes the instructions
4. Results are sent to an output device

Example:
Opening a web browser:
- Program stored on disk
- Loaded into RAM
- CPU executes instructions
- Output displayed on screen

---

# Why This Matters for Cybersecurity

Understanding computer architecture helps security professionals:

- Understand how malware executes
- Identify memory-based attacks
- Analyze system processes
- Investigate compromised machines

Many attacks target:
- Memory
- Processes
- System components

A strong understanding of how a computer works internally is therefore fundamental in cybersecurity.

---

# Key Concepts Learned
- Basic computer architecture
- CPU responsibilities
- RAM vs storage
- Input and output devices
- How components interact during program execution

---

# Progress Log
Room completed as part of my cybersecurity learning path on TryHackMe.