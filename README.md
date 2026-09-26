# Week 3: Password Cracking & Hash Extraction

## 📖 Overview
Welcome to the Week 3 Project Repository! This week focuses on the fundamentals of password cracking, hash extraction, and understanding why strong passwords are critical for data protection. 

In this project, we analyze a password-protected PDF file (`My Locked PDF1.pdf`,`My Locked PDF2.pdf`,`My Locked PDF3.pdf`) by extracting its underlying hash and using various cracking methodologies to recover the plaintext password.

## 🎯 Learning Objectives
By completing these modules, you will learn how to:
1. Understand the difference between **Encryption** (two-way) and **Hashing** (one-way).
2. Extract password hashes from secured documents (PDF, ZIP, Office).
3. Use command-line and GUI tools (**John the Ripper** & **Johnny**) to perform dictionary/brute-force attacks.
4. Utilize web-based tools (**Networkwalks Hash Calculator & Password Cracker**) for hash extraction and recovery.
5. Evaluate password complexity and the real-world risks of weak credentials.

---

## 📂 Project Modules

### 🛠️ Module 1: Password Cracking with John the Ripper (JTR)
**Tools Used:** John the Ripper (CLI), Johnny (GUI), Online Hash Extractor.  
**Task:** Extract the PDF hash using an online tool, save it to a `.txt` file, and use the Johnny GUI to configure and execute a password attack against `hash1.txt`.  
👉 [View Module 1 Documentation](./PM1-JohnTheRipper/README.md)

### 🌐 Module 2: Password Cracking with Networkwalks Tools
**Tools Used:** Networkwalks Hash Calculator, Networkwalks Password Cracker.  
**Task:** Upload the encrypted PDF directly to the browser-based Hash Calculator to retrieve the `$pdf$...` hash, then feed it into the Networkwalks Password Cracker to recover the password.  
👉 [View Module 2 Documentation](./PM2-NetworkwalksTools/README.md)

---

## 💻 Prerequisites & Environment
* **Operating System:** Windows 10/11 or Kali Linux (Tools are cross-platform).
* **Software:** 
  * [John the Ripper](https://www.openwall.com/john/)
  * [Johnny GUI](https://openwall.info/wiki/john/johnny)
* **Browser:** Any modern web browser (Chrome, Firefox, Edge) for the Networkwalks web tools.
* **Target File:** `My Locked PDF1.pdf``My Locked PDF2.pdf`,`My Locked PDF3.pdf` (Provided in the lab portal).

---

## 🧠 Key Takeaways & Theory
* **Hashing vs Encryption:** Encryption is a two-way function (can be decrypted with a key). Hashing is a one-way function that scrambles plain text to produce a unique message digest.
* **Password Complexity Matters:** A simple 8-character lowercase password can be cracked in minutes, while a 12-character mixed-case password can take years.
* **The Dark Web Reality:** Over 24 billion username/password pairs are circulating on the dark web. Reusing passwords across platforms is a massive security risk.

---

## ⚠️ Ethical Disclaimer
*The tools and techniques demonstrated in this repository are for **educational purposes and authorized security testing only**. Never attempt to crack passwords or access files that you do not own or do not have explicit, written permission to test. Unauthorized access to computer systems is illegal.*

---

## 📅 Timeline & Status
| Module | Task | Status |
| :--- | :--- | :---: |
| **PM1** | JTR & Johnny GUI Cracking | 🟩 Completed |
| **PM2** | Networkwalks Web Tools | 🟩 Completed |

---
<div align="center">
  <h3>👤 Author & Project Information</h3>
  <b>Pentester:</b> Aiman Atif | Cybersecurity Intern<br>
  <b>Program:</b> Networkwalks Cybersecurity Internship (Batch B083)<br>
  <b>Date:</b> 26-09-2026 </div>
