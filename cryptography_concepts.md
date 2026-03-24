# TryHackMe - Cryptography Concepts

## Introduction

Cryptography is the practice of securing information by transforming it into a protected format.

It is a core concept in cybersecurity used to ensure:

- confidentiality
- integrity
- authentication

Cryptography protects data from unauthorized access and ensures secure communication between systems.

---

## What is Cryptography?

Cryptography involves converting data into a form that is unreadable without the proper key.

It is used to protect sensitive information such as:

- passwords
- messages
- financial data

Cryptography relies on mathematical algorithms and keys to secure data.

---

## Key Concepts

### Plaintext

The original readable data.

---

### Ciphertext

The encrypted version of the data.

---

### Encryption

The process of converting plaintext into ciphertext.

---

### Decryption

The process of converting ciphertext back into plaintext.

---

### Key

A value used to encrypt and decrypt data.

The strength of cryptography depends on the secrecy and complexity of the key.

---

## Types of Cryptography

### Symmetric Cryptography

Uses a single key for both encryption and decryption.

Example:

- AES (Advanced Encryption Standard)

Advantages:

- fast and efficient

Disadvantages:

- key distribution is challenging

---

### Asymmetric Cryptography

Uses two keys:

- public key (shared)
- private key (kept secret)

Example:

- RSA

Advantages:

- secure key exchange

Disadvantages:

- slower than symmetric encryption

---

## Hashing

Hashing is a one-way process that converts data into a fixed-size value.

Example:

```
password → 5f4dcc3b5aa765d61d8327deb882cf99
```

Characteristics:

- cannot be reversed easily
- same input produces the same output

Used for:

- password storage
- data integrity verification

---

## Digital Signatures

Digital signatures are used to verify the authenticity and integrity of data.

They use asymmetric cryptography to:

- confirm the sender's identity
- ensure data has not been altered

---

## Why Cryptography Matters in Cybersecurity

Cryptography is essential for:

- securing communications (HTTPS, TLS)
- protecting stored data
- verifying identities
- preventing data tampering

Without cryptography, sensitive information would be exposed to attackers.

---

## Key Takeaways

- Cryptography protects data using mathematical techniques.
- Encryption converts plaintext into ciphertext.
- Symmetric uses one key; asymmetric uses two.
- Hashing ensures data integrity.
- Cryptography is essential for secure communication and data protection.

---

## Conclusion

The **Cryptography Concepts** module introduces the fundamental principles of securing data.

Understanding these concepts is essential for anyone working in cybersecurity, networking, or system administration.