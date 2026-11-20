# Week 03 – Password Cracking with John the Ripper & NetworkWalks Tools
| **Field** | **Detail** |
|---|---|
| **Pentester Name (Cybersecurity Professional)** | Fizza Mushtaq |
| **Program/Batch** | B084-NETWORKWALKS |
| **Intern ID** | NW-084-347 |
| **Date** | 20 November 2026 |
| **Modules Completed** | W3-PM1: Password Cracking with John the Ripper (JTR) <br> W3-PM2: Password Cracking with NetworkWalks Tools |
| **Client/Target** | 1. Provided password-protected PDF file for W3-PM1 <br> 2. Provided password-protected PDF file for W3-PM2 |
| **Practical Areas Covered** | **W3-PM1:** PDF hash extraction, password cracking with John the Ripper, and password verification. <br> **W3-PM2:** PDF hash extraction using NetworkWalks Hash Calculator, password recovery using NetworkWalks Password Cracker, and password verification. |
## Project Overview

This project covers two essential cybersecurity practicals focused on password recovery from encrypted PDF files. The labs demonstrate how password hashes are extracted and processed using password-cracking tools.

Both essential modules were completed using Kali Linux.

## Project Modules

### W3-PM1: Password Cracking with John the Ripper (JTR)

**Objective:** Recover the password of the provided encrypted PDF using John the Ripper.

**Tools Used:**
- Kali Linux
- John the Ripper
- pdf2john
- pdfinfo

**Practical Implementation:**

1. Verified the John the Ripper installation and build information.
2. Located the `pdf2john.pl` utility.
3. Extracted the password hash from the provided PDF file.
4. Saved the extracted hash in a text file.
5. Tested the PDF format and loaded the hash into John the Ripper.
6. Executed the password-cracking process.
7. Recovered the password successfully.
8. Verified the recovered password by opening the protected PDF and checking its information.

**Result:** Successfully recovered and verified the PDF password using John the Ripper.

**Screenshots:**

| No. | Screenshot |
|---|---|
| 1 | `01-JTR-Build-Info.png` |
| 2 | `02-PDF-Hash-Extraction.png` |
| 3 | `03-Hash-Loaded.png` |
| 4 | `04-Password-Recovery.png` |
| 5 | `05-Password-Verification.png` |
| 6 | `06-Unlocked-PDF.png` |

### W3-PM2: Password Cracking with NetworkWalks Tools

**Objective:** Recover the password of the provided PDF using NetworkWalks online tools.

**Tools Used:**
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Web Browser
- Kali Linux

**Practical Implementation:**

1. Opened the NetworkWalks Hash Calculator.
2. Uploaded the PDF provided specifically for the PM2 lab.
3. Extracted and copied the complete PDF hash.
4. Opened the NetworkWalks Password Cracker.
5. Submitted the extracted hash for password recovery.
6. Retrieved the recovered password.
7. Opened the original protected PDF and verified the password successfully.

**Result:** Successfully recovered the PDF password using NetworkWalks tools and verified access to the protected document.

**Screenshots:**

| No. | Screenshot |
|---|---|
| 1 | `01-NW-Hash-Calculator.png` |
| 2 | `02-NW-Password-Recovered.png` |
| 3 | `03-NW-PDF-Unlocked.png` |

## Optional Module

### AI-Assisted Password Cracking with Claude Desktop & HexStrike MCP

This optional module explores AI-assisted cybersecurity automation using Claude Desktop and the HexStrike MCP server.

The setup process was started, and the HexStrike server was successfully launched locally. However, the Claude Desktop MCP connection and practical execution were not completed.

This optional activity is separate from the two completed essential modules.

## Key Learning Outcomes

- Understanding PDF password protection and hash extraction.
- Working with John the Ripper in Kali Linux.
- Using `pdf2john` to extract PDF password hashes.
- Understanding the password-cracking workflow.
- Using NetworkWalks Hash Calculator and Password Cracker.
- Verifying recovered passwords against protected PDF files.
- Understanding the importance of strong passwords and secure file protection.

## Conclusion

Both essential Week 3 practical modules were successfully completed. The exercises provided hands-on experience with two different password-recovery approaches: a locally executed tool using John the Ripper and browser-based NetworkWalks tools.

All practical steps were performed on the provided lab files for educational purposes.

---

**Project:** Week 03 – Cybersecurity Practical Labs  
**Environment:** Kali Linux  
**Modules Completed:** W3-PM1 and W3-PM2  
**Evidence:** Screenshots of practical execution and results# Week-03-Password-Cracking-Lab
