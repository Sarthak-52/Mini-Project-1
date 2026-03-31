# OWASP Top 5 Vulnerability Simulator

An interactive, web-based simulator designed to demonstrate common web security vulnerabilities as defined by the OWASP Top 10. Created as an educational tool for **Jovac Group 8**.

![Vulnerability Simulator Mockup](https://images.unsplash.com/photo-1550751827-4bd374c3f58b?auto=format&fit=crop&q=80&w=1200)

## 🎯 Project Overview

This simulator provides a hands-on learning experience for understanding how critical web vulnerabilities work and how to mitigate them. It focuses on the top 5 vulnerabilities, offering interactive demonstrations where users can "exploit" weaknesses in a controlled environment to see the real-world impact.

## 🛠️ Vulnerabilities Covered

### 1. 🔐 Broken Access Control
Demonstrates **Insecure Direct Object Reference (IDOR)**. Users can attempt to bypass permission checks by manipulating user IDs in the simulation.

### 2. 🔒 Cryptographic Failures
Illustrates the difference between storing sensitive data (like passwords) in **Plaintext vs. Hashed** formats, emphasizing why encryption is critical.

### 3. 💉 Injection Attacks
A simulation of **SQL Injection**. Learn how improperly sanitized user inputs can lead to unauthorized data retrieval from a database.

### 4. 🧩 Insecure Design
Focuses on **Price Manipulation** and logic flaws. Demonstrates how poor design choices in the business logic can lead to financial or data loss.

### 5. ⚙️ Security Misconfiguration
Shows the dangers of **Verbose Error Logging**. Learn how detailed error messages can unintentionally leak sensitive system architecture details to attackers.

## 🚀 Getting Started

To run this project locally, follow these simple steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sarthak-52/Mini-Project-1.git
   ```
2. **Navigate to the project folder:**
   ```bash
   cd Mini-Project-1
   ```
3. **Open the Dashboard:**
   Simply open `new.html` in any modern web browser to start the simulation.

## 💻 Technologies Used

- **HTML5**: For semantic structure and layout.
- **Vanilla CSS**: Premium styling with a modern dark mode aesthetic, glassmorphism, and responsive grid layouts.
- **JavaScript**: For interactive simulations, vulnerability logic, and real-time feedback.
- **Google Fonts (Outfit)**: For clean, modern typography.

## 📚 Educational Purpose

This project is intended for educational and ethical hacking awareness only. It serves as a visual and interactive guide for students and developers to better understand web security principles and the importance of writing secure code.

---
*Created by Jovac Group 8 - March 2026*
