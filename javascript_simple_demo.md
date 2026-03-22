# TryHackMe - JavaScript Simple Demo

## Introduction

JavaScript is a widely used programming language primarily used for **web development**.

It allows developers to create dynamic and interactive web pages.  
In cybersecurity, JavaScript is also important for understanding:

- how web applications work
- client-side behavior
- potential vulnerabilities such as XSS (Cross-Site Scripting)

---

## What is JavaScript?

JavaScript is a **high-level, interpreted programming language** that runs in web browsers.

It enables interaction with web pages and user actions.

Example:

```javascript
console.log("Hello, World!");
```

This command prints a message in the browser console.

---

## Running JavaScript

JavaScript can be executed in different environments:

- directly in a web browser (console)
- inside HTML files
- using Node.js

Example in a browser console:

```javascript
console.log("Test");
```

---

## Variables

Variables are used to store data.

Example:

```javascript
let name = "Alice";
const age = 25;
```

- `let` → variable that can change
- `const` → constant value

---

## Data Types

Common JavaScript data types include:

- **string** → `"Hello"`
- **number** → `10`
- **boolean** → `true / false`
- **null**
- **undefined**

Example:

```javascript
let message = "Hello";
let number = 10;
let isActive = true;
```

---

## User Interaction

JavaScript can interact with users through the browser.

Example:

```javascript
let name = prompt("Enter your name:");
alert("Hello " + name);
```

---

## Basic Operations

JavaScript supports basic operations:

```javascript
let a = 5;
let b = 3;

console.log(a + b); // addition
console.log(a - b); // subtraction
console.log(a * b); // multiplication
console.log(a / b); // division
```

---

## Conditional Statements

Used to make decisions.

Example:

```javascript
let age = 18;

if (age >= 18) {
    console.log("Adult");
} else {
    console.log("Minor");
}
```

---

## Loops

### For loop

```javascript
for (let i = 0; i < 5; i++) {
    console.log(i);
}
```

### While loop

```javascript
let count = 0;

while (count < 5) {
    console.log(count);
    count++;
}
```

---

## Functions

Functions allow code reuse.

Example:

```javascript
function greet(name) {
    return "Hello " + name;
}

console.log(greet("Alice"));
```

---

## Why JavaScript Matters in Cybersecurity

JavaScript plays a key role in cybersecurity because:

- it is widely used in web applications
- many vulnerabilities are client-side (e.g., XSS)
- understanding JavaScript helps analyze web behavior
- attackers often use JavaScript in payloads

Security professionals must understand how JavaScript works to identify and exploit or prevent vulnerabilities.

---

## Key Takeaways

- JavaScript is essential for web development.
- It runs in browsers and allows dynamic interactions.
- Core concepts include variables, conditions, loops, and functions.
- It is important in cybersecurity for understanding web vulnerabilities.

---

## Conclusion

The **JavaScript Simple Demo** module introduces the fundamentals of JavaScript programming.

These basics are essential for understanding modern web applications and their security implications.