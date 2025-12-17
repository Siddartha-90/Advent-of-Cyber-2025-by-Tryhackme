# Advent-of-Cyber-2025-by-Tryhackme
A documented learning journey through TryHackMe's Advent of Cyber 2025. Contains detailed write-ups, scripts, and solution analysis to build core cybersecurity skills.

Advent of Cyber Prep Track:

# 🎄 Module 0: Advent of Cyber Prep (The Warm Up)

## 🕵️‍♂️ Scenario & Objective
**Location:** Wareville, Home of The Best Festival Company (TBFC)  
**Adversary:** King Malhare  
**Objective:** Prepare for the "SOCMAS" cyber attacks by completing 10 foundational missions.

This module serves as the onboarding phase for the Advent of Cyber 2025. Before investigating the main breaches, I am establishing a baseline in **Linux Navigation**, **Web Fundamentals**, and **Security Tools**.

---

## 📝 Mission Log (The 10 Challenges)
*The warm-up track consists of 10 specific challenges to test foundational skills.*

### 🔐 Security Basics & Windows
- [ ] **Challenge 1:** Password Pandemonium (Task 5) - *Password Security*
- [ ] **Challenge 2:** The Suspicious Chocolate.exe (Task 6) - *File Analysis*
- [ ] **Challenge 3:** Welcome to the AttackBox! (Task 7) - *Environment Setup*
- [ ] **Challenge 4:** The CMD Conundrum (Task 8) - *Windows Command Line*

### 🐧 Linux & Data Analysis
- [ ] **Challenge 5:** Linux Lore (Task 9) - *Linux Fundamentals*
- [ ] **Challenge 6:** The Leak in the List (Task 10) - *Grepping & Log Analysis*

### 🌐 Networking & Web
- [ ] **Challenge 7:** WiFi Woes in Wareville (Task 11) - *Wireless Security*
- [ ] **Challenge 8:** The App Trap (Task 12) - *Application Security*
- [ ] **Challenge 9:** The Chatbot Confession (Task 13) - *Prompt Injection / AI Safety*
- [ ] **Challenge 10:** The Bunny’s Browser Trail (Task 14) - *Digital Forensics / Browser History*

---

## 🧠 Technical Knowledge Base

### 🐧 1. Linux Command Line (CLI)
*Commands utilized during Challenge 5 & 6:*

| Command | Description | Example Usage |
| :--- | :--- | :--- |
| `ls -la` | List all files (including hidden `.files`) | `ls -la` |
| `cd` | Change Directory | `cd /home/ubuntu` |
| `cat` | Concatenate (Read file content) | `cat flag.txt` |
| `grep` | Global Regular Expression Print (Search text) | `grep "password" logs.txt` |

### 💻 2. Windows & CMD
*Commands utilized during Challenge 4:*
* **`dir`**: Lists files in the current directory (Windows version of `ls`).
* **`type`**: Displays the contents of a text file (Windows version of `cat`).

### 🛡️ 3. Security Fundamentals
* **Password Hygiene:** Understanding entropy and why "password123" is easily cracked.
* **Malware Indicators:** Identifying suspicious file extensions (like `.exe` disguised as a document).
* **Metadata:** Hidden data inside files (e.g., browser history or image properties) that reveals user activity.

---

## 💡 Student Reflection
*Why this matters for my career:*
Completing these 10 missions reinforced that **enumeration** (gathering info) is the most critical step in cybersecurity. From analyzing Windows logs to filtering Linux files with `grep`, I learned that the command line is an essential tool for both Red and Blue teams.
