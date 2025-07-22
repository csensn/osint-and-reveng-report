# OSINT & Reverse Engineering Report

## 🔍 OSINT Objective

- Identify the email address of a person using the alias `Monkey D. Tuffy`
- Used [WhatsMyName](https://whatsmyname.app/) and GitHub enumeration
- Discovered a repository containing a `contact.php` page
- 📧 **Email Found:** `****************@simplelogin.fr`

## 🧠 Reverse Engineering Objective

- Analyzed an obfuscated JavaScript file (`obf.js`)
- Used [obf-io.deobfuscate.io](https://obf-io.deobfuscate.io/) for initial readability
- Identified RC4-like logic used for decryption
- Patched the script to replace browser-based `prompt()` and `fetch()` with hardcoded inputs
- Executed with Node.js to retrieve the flag

### ✅ Output
- 🏁 **Flag:** `flag{**_**_*******}`

## 📄 Report

See full documentation in [`OSINT_RevEng_Report.pdf`](./OSINT_Reverse Engineering Report.pdf)

---

## 🧰 Tools Used
- WhatsMyName
- GitHub Recon
- Node.js
- JavaScript (TextEncoder, Uint8Array)
- RC4 Cipher Logic

---

## 📌 Notes
This project was completed as part of an interview evaluation and showcases my ability to:
- Perform structured OSINT investigations
- Reverse obfuscated JS logic
- Adapt browser-based code to run offline via Node.js

---
**Author:** Narendra Singh Naruka  
📧 nsnaruka06@gmail.com  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/csensn)
