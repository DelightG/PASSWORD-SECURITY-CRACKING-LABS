
# 🛡️ PASSWORD SECURITY & CRACKING LABS

### 🔐 Password Security | Hash Analysis | Password Recovery

![Cybersecurity](https://img.shields.io/badge/Cybersecurity-Password_Security-042755?style=for-the-badge)
![Networkwalks](https://img.shields.io/badge/Networkwalks-Batch_B084-D4A017?style=for-the-badge)
![Week](https://img.shields.io/badge/Week-03-042755?style=for-the-badge)

**Prepared by:** Ndidiamaka Okorie  
**Program:** Networkwalks Cybersecurity Training  
**Batch:** B084
**Project:** Week 3 – Password Security & Cracking Labs  
**Environment:** Windows  
**Status:** Practical Documentation

---

## 📌 1. Project Overview

This project focuses on understanding password security through practical cybersecurity exercises involving password hashes, password recovery tools, and protected PDF documents.

The lab introduces two approaches to password-security testing:

- **Module 1:** John the Ripper and Johnny GUI
- **Module 2:** Networkwalks Hash Calculator and Password Cracker

The purpose is to understand how password-recovery tools operate, how password strength affects security, and why proper documentation is important during cybersecurity assessments.

All practical testing is intended for authorized laboratory files only.

---

## 🎯 2. Project Objectives

The objectives of this project are to:

- Understand password hashing and password protection.
- Install and configure John the Ripper.
- Understand how Johnny GUI works.
- Extract password-related hashes from protected PDF files.
- Save and manage extracted hashes.
- Learn how password-recovery tools test candidate passwords.
- Explore the Networkwalks Hash Calculator.
- Explore the Networkwalks Password Cracker.
- Verify recovered passwords against authorized PDF files.
- Document practical activities using screenshots.
- Understand the importance of strong passwords.

---

## 🛠️ 3. Tools and Technologies

| Tool | Purpose |
|------|---------|
| Windows | Laboratory operating system |
| John the Ripper | Password recovery and auditing |
| Johnny GUI | Graphical interface for John the Ripper |
| Networkwalks Hash Calculator | PDF hash extraction |
| Networkwalks Password Cracker | Password-recovery exercise |
| Protected PDF | Authorized testing document |
| Text Editor | Saving extracted hashes |
| GitHub | Project documentation |
| Screenshots | Practical evidence |

---

# ⚔️ MODULE 1: JOHN THE RIPPER & JOHNNY GUI

## 📌 4. Introduction

John the Ripper is a password-security auditing tool used to evaluate password strength and perform authorized password-recovery exercises.

Johnny provides a graphical interface that makes it easier to interact with John the Ripper.

This module covers the installation process, configuration, hash preparation, password-recovery workflow, and verification.

---

## 🔹 5. Installing John the Ripper

The first stage involves obtaining and preparing John the Ripper for use on Windows.

### Procedure

1. Obtain John the Ripper from a trusted source.
2. Extract the downloaded package.
3. Open the extracted directory.
4. Locate the `run` folder.
5. Identify the `john.exe` executable.
6. Confirm that the required program files are available.

### 📸 Evidence

![John the Ripper Files](module-1-jtr/evidence/jtr-files.png)

---

## 🔹 6. Installing Johnny GUI

Johnny GUI provides a graphical interface for working with John the Ripper.

### Procedure

1. Download the Johnny installer.
2. Launch the installation wizard.
3. Select the installation directory.
4. Choose the required components.
5. Complete the installation.
6. Launch Johnny GUI.

### 📸 Evidence

![Johnny Installation](module-1-jtr/evidence/johnny-installation.png)

![Johnny Setup](module-1-jtr/evidence/johnny-setup.png)

---

## 🔹 7. Configuring Johnny

After installation, Johnny must be linked to the John the Ripper executable.

### Procedure

1. Open Johnny GUI.
2. Navigate to the relevant configuration settings.
3. Locate the John the Ripper executable.
4. Select `john.exe` from the JTR installation directory.
5. Save the configuration.
6. Confirm that Johnny recognizes the executable.

### 📸 Evidence

![Johnny Configuration](module-1-jtr/evidence/johnny-configuration.png)

---

## 🔹 8. Extracting the PDF Hash

Password-protected PDF files contain security information that can be represented in a format suitable for password-recovery testing.

For this exercise, the target must be an authorized laboratory PDF.

### Procedure

1. Obtain the protected PDF provided for the exercise.
2. Use the appropriate PDF hash-extraction tool.
3. Extract the password-related hash.
4. Confirm that the output is in the expected PDF hash format.
5. Save the complete extracted value.

A typical PDF hash representation begins with:

`$pdf$`

### 📸 Evidence

![PDF Hash Extraction](module-1-jtr/evidence/pdf-hash-extraction.png)

---

## 🔹 9. Saving the Extracted Hash

The extracted PDF hash can be stored in a text file for use during password-recovery testing.

Example filenames:

```text
hash1.txt
hash2.txt
hash3.txt
```

Each file should contain the correct hash information obtained from the authorized laboratory document.

### 📸 Evidence

![Saved Hash](module-1-jtr/evidence/saved-hash.png)

---

## 🔹 10. Password Recovery with Johnny

The saved hash file can be loaded into Johnny for authorized password-recovery testing.

### Procedure

1. Launch Johnny GUI.
2. Load the prepared hash file.
3. Confirm that the hash is recognized.
4. Select the appropriate recovery settings.
5. Start the authorized password-recovery process.
6. Observe and document the results.

The time required for password recovery depends on password complexity, the search method, and available computing resources.

### 📸 Evidence

![Johnny Password Recovery](module-1-jtr/evidence/johnny-password-recovery.png)

---

## 🔹 11. Password Verification

If a password is successfully recovered, it should be verified against the original authorized PDF.

### Procedure

1. Open the protected PDF.
2. Enter the recovered password.
3. Check whether the document opens.
4. Record the verification result.
5. Capture a screenshot of the result.

**My verification result:** Pending actual lab evidence.

### 📸 Evidence

![PDF Verification](module-1-jtr/evidence/pdf-verification.png)

---

# 🌐 MODULE 2: NETWORKWALKS PASSWORD SECURITY TOOLS

## 📌 12. Introduction

The second module introduces browser-based tools used during the Networkwalks password-security practical.

The tools include:

- Networkwalks Hash Calculator
- Networkwalks Password Cracker

This module focuses on extracting a PDF hash, submitting it for authorized password-recovery testing, and verifying the result.

---

## 🔹 13. Networkwalks Hash Calculator

The Hash Calculator is used to obtain the password-related hash from the authorized protected PDF.

### Procedure

1. Open the Networkwalks Hash Calculator.
2. Select the authorized PDF document.
3. Upload the document as instructed.
4. Generate the PDF hash.
5. Copy the complete hash value.
6. Preserve the output for the next stage.

### 📸 Evidence

![Networkwalks Hash Calculator](module-2-networkwalks-tools/evidence/hash-calculator.png)

![Generated PDF Hash](module-2-networkwalks-tools/evidence/generated-pdf-hash.png)

---

## 🔹 14. Networkwalks Password Cracker

The Password Cracker is used to perform the password-recovery exercise using the extracted hash.

### Procedure

1. Open the Networkwalks Password Cracker.
2. Locate the hash input field.
3. Paste the complete extracted PDF hash.
4. Start the authorized recovery process.
5. Observe the tool's output.
6. Record the result.

### 📸 Evidence

![Networkwalks Password Cracker](module-2-networkwalks-tools/evidence/password-cracker.png)

---

## 🔹 15. Verifying the Password

After the recovery process, the result should be tested against the original protected PDF.

### Procedure

1. Open the original PDF.
2. Enter the recovered password, if available.
3. Check whether the document opens.
4. Document the result.
5. Save the verification screenshot.

**My verification result:** Pending actual lab evidence.

### 📸 Evidence

![Password Verification](module-2-networkwalks-tools/evidence/password-verification.png)

---

# 📊 16. Comparison of Both Modules

| Feature | John the Ripper / Johnny | Networkwalks Tools |
|---------|--------------------------|--------------------|
| Interface | Desktop application | Web browser |
| Main purpose | Password auditing and recovery | PDF password-recovery exercise |
| Input | Extracted PDF hash | Extracted PDF hash |
| Hash preparation | Local extraction workflow | Hash Calculator |
| Recovery | John the Ripper | Networkwalks Password Cracker |
| Verification | Protected PDF | Protected PDF |
| Documentation | Screenshots | Screenshots |

---

# 🔎 17. Key Observations

### Password Complexity

Long and unpredictable passwords are generally more resistant to password-recovery attempts.

### Hash Handling

An incomplete or incorrectly formatted hash may prevent a password-recovery tool from processing the input successfully.

### Tool Configuration

Local password-recovery tools require the correct installation paths and configuration settings.

### Documentation

Screenshots, recorded procedures, and actual results make cybersecurity projects easier to review and reproduce.

---

# 🔐 18. Security Recommendations

The following practices can improve password security:

1. Use strong and unique passwords.
2. Avoid predictable password patterns.
3. Use a reputable password manager.
4. Enable multi-factor authentication where available.
5. Avoid reusing passwords across accounts.
6. Protect sensitive files and password-related information.
7. Carry out security testing only with authorization.
8. Maintain proper records of security assessments.

---

# 📁 19. Project Folder Structure

```text
NETWORKWALKS-WEEK3-PASSWORD-SECURITY-LABS/
│
├── README.md
│
├── module-1-jtr/
│   └── evidence/
│       ├── jtr-files.png
│       ├── johnny-installation.png
│       ├── johnny-setup.png
│       ├── johnny-configuration.png
│       ├── pdf-hash-extraction.png
│       ├── saved-hash.png
│       ├── johnny-password-recovery.png
│       └── pdf-verification.png
│
└── module-2-networkwalks-tools/
    └── evidence/
        ├── hash-calculator.png
        ├── generated-pdf-hash.png
        ├── password-cracker.png
        └── password-verification.png
```

---

# 📸 20. Practical Evidence

The project evidence will be organized into two folders:

**Module 1 Evidence**

`module-1-jtr/evidence/`

**Module 2 Evidence**

`module-2-networkwalks-tools/evidence/`

Each screenshot should show the relevant step performed during the practical.

The screenshots referenced in this README must be uploaded to the corresponding folders before they will display on GitHub.

---

# 📚 21. Skills and Knowledge

This project is designed to develop practical knowledge in:

- Password security fundamentals
- Password hashing concepts
- John the Ripper
- Johnny GUI configuration
- PDF hash extraction
- Password-recovery workflows
- Security testing ethics
- Evidence documentation
- Cybersecurity reporting

---

# 📝 22. Conclusion

The Week 3 Password Security & Cracking Labs provide an opportunity to understand how password protection works and how authorized password-recovery tools can be used to evaluate password security.

The exercises cover two approaches: using John the Ripper with Johnny GUI and using the Networkwalks browser-based tools.

Through these activities, the project emphasizes the importance of strong passwords, correct tool configuration, careful handling of hashes, and accurate technical documentation.

Actual recovery outcomes and supporting screenshots will be added as the practical exercises are completed.

---

## ⚠️ Disclaimer

This project is intended strictly for cybersecurity education and authorized laboratory testing.

Password-recovery techniques must not be used against files, accounts, or systems without permission.

---

### 👩🏽‍💻 Project Author

**Ndidiamaka Okorie**  
Networkwalks Cybersecurity Training  
**Batch B084 | Week 03**

*Learning, Practising, and Building Practical Cybersecurity Skills.*
