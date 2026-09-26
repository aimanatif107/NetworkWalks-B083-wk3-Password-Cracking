# Module 1: Password Cracking with John the Ripper (JTR) & Johnny GUI

## 🎯 Objective
In this module, we will extract the hash from a password-protected PDF file (`My Locked PDF1.pdf`) and use **John the Ripper (JTR)** along with its graphical interface **Johnny** to perform a password cracking attack and recover the plaintext password.

## 🛠️ Prerequisites & Tools
* **Target File:** `My Locked PDF1.pdf`
* **John the Ripper (JTR):** [Download Link](https://www.openwall.com/john/)
* **Johnny GUI:** [Download Link](https://openwall.info/wiki/john/johnny)
* **Online Hash Extractor:** [OnlineHashCrack PDF Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php)
* *Note: If using Kali Linux, JTR is pre-installed.*

---

## 📝 Step-by-Step Solution

### Step 1: Install and Configure Johnny GUI
1. Download and install **Johnny** on your Windows PC.
2. Open Johnny and navigate to **Settings**.
3. Browse and select the `john.exe` file. 
   * *Note: The `john.exe` file is located inside the `run` folder of your John the Ripper installation directory.*

### Step 2: Extract the PDF Hash
1. Open the [OnlineHashCrack PDF Hash Extractor](https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php) in your web browser.
2. Upload `My Locked PDF1.pdf` and click **Upload**.
3. Copy the generated hash value. 
   * ⚠️ **Important:** If the hash starts with extra characters like `b'`, remove them. The hash must start exactly with `$pdf$...`

### Step 3: Save the Hash to a Text File
1. Open **Notepad** on your Windows PC.
2. Paste the cleaned hash value into Notepad.
3. Save the file as `hash1.txt` in your project directory.

### Step 4: Crack the Password using Johnny
1. Open **Johnny** and click on **Open password file**.
2. Browse to and select your `hash1.txt` file.
3. Click on **Start new attack**.
4. Wait for the tool to process the hash. Depending on your CPU and password complexity, this may take a few moments.

### Step 5: Verify the Cracked Password
1. Open `My Locked PDF1.pdf` in your PDF reader.
2. When prompted, enter the cracked password: **`password1`**
3. The PDF will successfully open, confirming the crack was successful.

---

## 🧠 Key Takeaways & Industry Context
* **Hashing vs. Encryption:** Encryption is a two-way function (can be decrypted with a key). Hashing is a one-way function that scrambles plain text into a unique message digest.
* **Real-World Impact:** Weak passwords and credential stuffing lead to massive breaches. Recent African cybersecurity incidents highlight this risk:
  * **2026 (South Africa):** MTN Group's 2025 breach escalated, affecting over 5,700 customers in Ghana.
  * **2025 (Namibia):** Telecom Namibia refused to pay ransom; attackers leaked billing data of senior officials.
  * **2024 (Nigeria):** Fintech giant Flutterwave was hacked, diverting ~$7 million from customer accounts.
  * **2024 (South Africa):** Cell C breach exposed 2TB of data from 7.7 million customers.

---
