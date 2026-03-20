# TryHackMe - Data Encoding

## Introduction

Data encoding is the process of converting data into a different format so that it can be easily stored, transmitted, or processed by systems.

Unlike encryption, encoding is **not meant to secure data**, but rather to ensure compatibility between different systems.

Encoding is widely used in computing, networking, and web technologies.

---

## What is Encoding?

Encoding transforms data from one representation into another using a specific format or scheme.

Example:

Plaintext:

```
Hello
```

Base64 encoded:

```
SGVsbG8=
```

The encoded data can be decoded back to its original form.

---

## Encoding vs Encryption

It is important to distinguish between encoding and encryption:

- **Encoding** → for data format compatibility (reversible without a secret key)
- **Encryption** → for data protection (requires a key)
- **Hashing** → one-way transformation (cannot be reversed)

Encoding does **not provide security**.

---

## Common Encoding Methods

### Base64

Base64 is one of the most commonly used encoding schemes.

It converts binary data into ASCII characters.

Example:

```
Hello → SGVsbG8=
```

Used in:

- email attachments
- web data (e.g., APIs, JSON)
- encoding binary data in text formats

---

### URL Encoding

Used to encode characters in URLs so they can be safely transmitted over the internet.

Example:

```
space → %20
```

Used in:

- web requests
- query parameters

---

### ASCII Encoding

ASCII assigns numerical values to characters.

Example:

```
A → 65
```

Binary representation:

```
01000001
```

---

### Unicode Encoding

Unicode extends ASCII to support a wide range of characters and languages.

Common formats include:

- UTF-8
- UTF-16

Used for:

- international text
- modern web applications

---

## Why Encoding Matters in Cybersecurity

Encoding is frequently encountered in cybersecurity tasks such as:

- analyzing network traffic
- inspecting web requests and responses
- decoding data in logs
- identifying obfuscated data

Attackers may use encoding to **hide payloads or bypass filters**, so understanding encoding helps detect suspicious behavior.

---

## Common Use Cases

- transmitting binary data over text-based protocols
- encoding data in URLs
- formatting data for APIs
- storing data in a standardized format

---

## Key Takeaways

- Encoding converts data into a different format for compatibility.
- It is reversible and does not require a secret key.
- Base64, URL encoding, ASCII, and Unicode are common encoding methods.
- Encoding is not a security mechanism.
- Understanding encoding is useful for analyzing data in cybersecurity.

---

## Conclusion

Data encoding is essential for ensuring that data can be transmitted and understood across different systems.

While it does not provide security, it plays a crucial role in data processing, communication, and cybersecurity analysis.