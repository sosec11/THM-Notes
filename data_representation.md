# TryHackMe - Data Representation

## Introduction

Computers do not understand human-readable data such as text, images, or numbers directly.  
Instead, all information inside a computer is represented using **binary**, a system based on two digits: **0 and 1**.

Data representation explains how different types of information are converted into binary so that computers can store, process, and transmit data.

Understanding how data is represented is important in cybersecurity because it helps analysts understand how systems process and manipulate information.

---

## Binary System

Binary is the base-2 number system used by computers.

It uses only two digits:

- **0**
- **1**

Each digit in a binary number is called a **bit** (binary digit).

Example:

Binary number:

```
1011
```

This number represents a value in base-2 rather than base-10.

Binary is the fundamental language used by computer hardware and operating systems.

---

## Bits and Bytes

A **bit** is the smallest unit of data in computing.

- 1 bit = 0 or 1

A **byte** is a group of 8 bits.

Example:

```
01001000
```

This sequence of 8 bits represents one byte.

Bytes are commonly used to represent characters, numbers, and other types of data.

---

## Decimal System

Humans typically use the **decimal system (base-10)**.

It uses ten digits:

0 1 2 3 4 5 6 7 8 9

Computers convert decimal numbers into binary so they can process them internally.

Example:

Decimal:

```
10
```

Binary:

```
1010
```

Understanding the conversion between decimal and binary is important when working with computer systems.

---

## Hexadecimal

Hexadecimal is a **base-16 number system** often used in computing because it is easier to read than binary.

It uses sixteen characters:

```
0 1 2 3 4 5 6 7 8 9 A B C D E F
```

Where:

- A = 10
- B = 11
- C = 12
- D = 13
- E = 14
- F = 15

Example:

Binary:

```
1111
```

Hexadecimal:

```
F
```

Hexadecimal is widely used in:

- memory addresses
- color codes
- debugging
- cybersecurity tools

---

## Character Encoding

Computers represent text using **character encoding systems**.

One common encoding standard is **ASCII** (American Standard Code for Information Interchange).

ASCII assigns numbers to characters.

Example:

```
A = 65
```

Binary representation:

```
01000001
```

More advanced encoding systems like **Unicode** allow computers to represent many languages and symbols.

---

## Why Data Representation Matters in Cybersecurity

Understanding data representation helps cybersecurity professionals:

- analyze raw data
- understand file structures
- interpret network traffic
- identify encoded or obfuscated data
- analyze malware behavior

Binary and hexadecimal formats are commonly used in **security tools, packet analysis, and forensic investigations**.

---

## Key Takeaways

- Computers represent all data using **binary (0 and 1)**.
- A **bit** is the smallest unit of data.
- A **byte** consists of **8 bits**.
- Humans commonly use **decimal**, while computers use **binary**.
- **Hexadecimal** is a compact representation of binary.
- Character encoding systems such as **ASCII** convert text into numerical values.

---

## Conclusion

Data representation explains how computers store and process information internally.

Understanding binary, hexadecimal, and encoding systems provides a strong foundation for working with computer systems and cybersecurity tools.