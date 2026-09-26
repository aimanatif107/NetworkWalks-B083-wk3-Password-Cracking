# Module 2: Password Cracking with Networkwalks Web Tools

## 🎯 Objective
In this module, we will utilize browser-based tools provided by Networkwalks to extract a hash from a locked PDF and crack it without installing any local software. This demonstrates how accessible password cracking tools are via the web.

## 🛠️ Prerequisites & Tools
* **Target File:** `My Locked PDF1.pdf`
* **Networkwalks Hash Calculator:** [https://networkwalks.com/hash-calculator/](https://networkwalks.com/hash-calculator/)
* **Networkwalks Password Cracker:** [https://networkwalks.com/password-cracker/](https://networkwalks.com/password-cracker/)

---

## 📝 Step-by-Step Solution

### Step 1: Extract the Hash using Networkwalks Hash Calculator
1. Open the [Networkwalks Hash Calculator](https://networkwalks.com/hash-calculator/) in your web browser.
2. Upload the locked file `My Locked PDF1.pdf`.
3. The tool will parse the file and output the hash value, which will start with `$pdf$...`
4. **Copy the complete hash value.** Do not miss any characters.
> 📸 **[Insert Screenshot: Networkwalks Hash Calculator showing the uploaded file and the extracted $pdf$... hash]**

### Step 2: Crack the Hash using Networkwalks Password Cracker
1. Open the [Networkwalks Password Cracker](https://networkwalks.com/password-cracker/) in your web browser.
2. Paste the copied hash value into the input field.
3. Start the attack. The tool will run a dictionary/brute-force attempt against the hash.
4. Wait for the tool to finish. The time taken depends on the complexity of the password.
> 📸 **[Insert Screenshot: Networkwalks Password Cracker showing the hash being processed and the final cracked password]**

### Step 3: Verify the Cracked Password
1. Open `My Locked PDF1.pdf` on your local machine.
2. Enter the cracked password: **`password1`**
3. The document will unlock, proving the hash was successfully reversed to its plaintext form.
> 📸 **[Insert Screenshot: The unlocked PDF document open on your screen]**

---

## 🧠 Key Takeaways & Industry Context
* **The Danger of Weak Passwords:** A simple 8-character password using only lowercase letters can be cracked in minutes. A strong 12-character mixed-case password can take years.
* **The Dark Web Reality:** Over **24 billion** username and password pairs are currently available on the dark web from past breaches. 
* **Common Passwords:** "123456" and "password" remain among the most used passwords globally every year.
* **Recent Leak Example:** In 2025, a global leak of around 183 million Gmail login details demonstrated how old stolen passwords keep circulating and being reused for years.
* **Best Practice:** Always use a Password Manager and enable Multi-Factor Authentication (MFA) to protect against credential stuffing and hash cracking.

---
