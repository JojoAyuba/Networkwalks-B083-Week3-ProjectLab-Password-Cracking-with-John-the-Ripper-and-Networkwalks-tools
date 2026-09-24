# Password-Cracking-with-John-the-Ripper-and-Networkwalks-tools-Week-3-Project-Task-Lab-
A hands-on internship project covering password recovery of a protected PDF file using two different approaches: John the Ripper (JTR), and the Networkwalks online Hash Calculator &amp; Password Cracker tools.

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red) ![John the Ripper](https://img.shields.io/badge/John%20the%20Ripper-JTR-blue) ![Johnny](https://img.shields.io/badge/Johnny-GUI-lightgrey) ![Networkwalks Tools](https://img.shields.io/badge/Networkwalks-Tools-lightgrey) ![Skill](https://img.shields.io/badge/Skill-Password%20Cracking-red) ![Skill](https://img.shields.io/badge/Skill-Hash%20Extraction-red) ![Ethical Hacking](https://img.shields.io/badge/Ethical-Hacking-orange) ![Networkwalks](https://img.shields.io/badge/Networkwalks-grey) ![Author](https://img.shields.io/badge/Author-Josiah%20Ayuba-red)


## 📌 About This Project

This project documents two practical exercises completed during Week 3 of my Cybersecurity internship at Networkwalks: cracking the password of a protected PDF file (`My Locked PDF1.pdf`) using two different methods — John the Ripper via command line in Kali Linux, and the Networkwalks Hash Calculator & Password Cracker web tools.

Both exercises target the same locked PDF, so together they compare a local offline cracking tool against a browser-based online cracking tool, showing two valid approaches to the same recovery task.

## 🛡️ Liability Disclaimer

I carried out these activities only on a file provided for training purposes as part of my Networkwalks Cybersecurity internship. These materials are for educational purposes only. I understand that unauthorized access or misuse of these techniques against files or systems I do not own or have permission to test is illegal, and that every action taken with this knowledge is my own responsibility.


# 🛡️  Tools & Technologies

| **Tool / Technology** | **Purpose** |
|---|---|
|  **Windows** | Primary practical environment |
|  **John the Ripper** | Password-security testing and password recovery |
|  **Johnny GUI** | Graphical interface for John the Ripper |
|  **Web Browser** | Accessing Networkwalks security tools |
|  **Networkwalks Hash Calculator** | Extracting the PDF hash |
|  **Networkwalks Password Cracker** | Password-recovery exercise |
|  **Protected PDF** | Authorized laboratory target |
|  **PDF Hash** | Input for password-recovery workflows |
|  **hash1.txt** | Stored PDF hash for the JTR workflow |
|  **hash2.txt** | Stored PDF hash for the JTR workflow |
|  **hash3.txt** | Stored PDF hash for the JTR workflow |
|  **Screenshots** | Practical evidence and documentation |

---

# 🛡️  Module 01 Password Cracking with John the Ripper

##   Module Overview

The first practical focused on **John the Ripper (JTR)** and its graphical interface, **Johnny**.

The exercise involved working with an authorized protected PDF, extracting the corresponding PDF hash, loading the hash into Johnny, initiating password recovery, and verifying the recovered password against the protected PDF.

## 🛠️ Module Environment

| **Component** | **Details** |
|---|---|
|  **Platform** | Windows PC |
|  **Password Tool** | John the Ripper |
|  **GUI** | Johnny |
|  **Target** | Authorized Protected PDF |
|  **Input** | PDF Hash |
|  **Hash File** | `hash1.txt` |
|  **Hash File** | `hash2.txt` |
|  **Hash File** | `hash3.txt` |
|  **Verification** | Protected PDF |

---

##   Practical Procedure

### 🔹  Obtain John the Ripper

John the Ripper was obtained for the Windows environment as required for the laboratory exercise.

---

### 🔹  Configure Johnny

Johnny GUI was configured to work with the John the Ripper installation.

The `john.exe` executable was selected from the appropriate JTR `run` directory.

---

### 🔹 Obtain the Protected PDF

The protected PDF supplied for the cybersecurity practical was used as the authorized laboratory target.

---

### 🔹 Extract the PDF Hash

The protected PDF was processed to obtain its corresponding password hash.

The resulting hash followed the expected PDF hash format beginning with:

```text
$pdf$
```

---

### 🔹  Create the Hash File

The extracted hash was saved into a text file:

```text
hash1.txt
```

The hash was preserved as required so that it could be loaded into Johnny.

---

### 🔹  Load the Hash into Johnny

The saved hash file was loaded through Johnny using the password-file workflow.

This provided JTR with the required hash input for the laboratory exercise.

---

### 🔹  Start Password Recovery

A password-recovery process was initiated through Johnny.

The recovery process demonstrated how password-security tools can test candidate passwords against a supplied password hash.

Recovery time can vary depending on factors such as:

- Password complexity
- Candidate search space
- System performance
- Available processing resources
- Attack configuration

---

### 🔹 Verify the Recovered Password

The recovered password was used to open the protected PDF.

Successful opening of the PDF provided verification that the password-recovery process had produced the expected result.

---
### 🔹 Screenshot Evidence Using JTR

![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 001522.png>)
![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 000443.png>)
![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 000810.png>)
![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 000944.png>)
![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 001406.png>)

---

# 🛡️  Module 02 Password Cracking with Networkwalks Tools

##   Module Overview

The second practical focused on browser-based password-security tools provided as part of the Networkwalks training exercise.

The module used:

- **Networkwalks Hash Calculator**
- **Networkwalks Password Cracker**

The workflow involved extracting the PDF hash, copying the complete hash value, submitting it to the password-recovery tool, and verifying the resulting password against the protected PDF.

---

##   Module Environment

| **Component** | **Details** |
|---|---|
| 💻 **Platform** | Windows Laptop |
| 🌐 **Interface** | Web Browser |
| 🔎 **Hash Tool** | Networkwalks Hash Calculator |
| ⚔️ **Recovery Tool** | Networkwalks Password Cracker |
| 📄 **Target** | Authorized Protected PDF |
| #️⃣ **Input** | PDF Hash |

---

##   Practical Procedure

### 🔹  Obtain the Encrypted PDF

The protected PDF supplied for the laboratory exercise was obtained and used as the authorized target.

---

### 🔹  Open the Hash Calculator

The Networkwalks Hash Calculator was opened through a web browser.

---

### 🔹  Upload the PDF

The protected PDF was uploaded to the Hash Calculator.

The tool generated the corresponding PDF hash.

The generated value followed the expected:

```text
$pdf$
```

format.

---

### 🔹  Copy the Complete Hash

The complete hash value was copied for use during the next stage.

Preserving the complete hash was important because the entire value represents the required input for the password-recovery workflow.

---

### 🔹  Open the Password Cracker

The Networkwalks Password Cracker was opened in the browser.

---

### 🔹  Submit the Hash

The extracted PDF hash was submitted to the Password Cracker and the recovery process was initiated.

---

### 🔹  Verify the Result

After the password-recovery process completed, the recovered password was used to open the protected PDF.

Successful access to the document provided verification of the recovery result.

---

### 🔹 Screenshot Evidence Using Networkwalks Tools

![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 002710.png>)
![Screenshot Evidence Using JTR](<Screenshot 2026-09-24 003010.png>)

---

# 🛡️  Module Comparison

| **Category** | **Module 01 JTR** | **Module 02 Networkwalks Tools** |
|---|---|---|
| **Primary Tool** | John the Ripper | Networkwalks Password Cracker |
| **Interface** | Johnny GUI | Web Browser |
| **Hash Extraction** | PDF hash extraction workflow | Networkwalks Hash Calculator |
| **Target** | Protected PDF | Protected PDF |
| **Hash Format** | `$pdf$...` | `$pdf$...` |
| **Environment** | Windows | Web Browser |
| **Recovery Process** | JTR-based | Networkwalks tool |
| **Verification** | Open protected PDF | Open protected PDF |
| **Evidence** | Screenshots | Screenshots |

##  Results Summary

| **Result** | **Module 01 JTR / Johnny** | **Module 02 Networkwalks Tools** |
|---|---|---|
|  **Hash Extraction** | ✅ Successful | ✅ Successful |
|  **Password Recovery** | ✅ Successful | ✅ Successful |
|  **Password Recovered** | ✅ Yes | ✅ Yes |
|  **PDF Verification** | ✅ Successfully Opened | ✅ Successfully Opened |
|  **Evidence Captured** | ✅ Yes | ✅ Yes |
|  **Overall Result** | **COMPLETED** | **COMPLETED** |

---

---

# 🛡️  Password Security Concepts

##    Password Cracking

Password cracking refers to the process of recovering a password from a password-related representation such as a hash or protected-file credential mechanism.

In a legitimate cybersecurity context, password-recovery techniques can be used to evaluate password strength and demonstrate the risks associated with weak credentials.

---

##     Hashing

Hashing transforms data into a derived representation known as a hash or message digest.

In this practical, the PDF hash served as an input to the password-recovery workflows.

The important concept demonstrated was that security tools can operate against password-related representations rather than directly modifying the protected file.

---

## 🔄  Encryption vs Hashing

Encryption and hashing serve different security purposes.

```text
ENCRYPTION
Plaintext
   ↓
Encryption
   ↓
Ciphertext
   ↓
Decryption with appropriate key
   ↓
Plaintext


HASHING
Input
   ↓
Hash Function
   ↓
Hash / Digest
```

Encryption is designed to be reversible when the appropriate key is available, while cryptographic hashing is generally designed as a one-way transformation.

The protected PDF exercise provided a practical demonstration of how password protection and password-recovery workflows can be analyzed during authorized security testing.

---

# 🛡️  Skills Demonstrated

<p align="center">

<img src="https://img.shields.io/badge/PASSWORD%20SECURITY-C00000?style=for-the-badge" />
<img src="https://img.shields.io/badge/HASH%20ANALYSIS-238F89?style=for-the-badge" />
<img src="https://img.shields.io/badge/JOHN%20THE%20RIPPER-0070C0?style=for-the-badge" />
<img src="https://img.shields.io/badge/JOHNNY-E87500?style=for-the-badge" />
<img src="https://img.shields.io/badge/EVIDENCE%20COLLECTION-404040?style=for-the-badge" />

</p>

### Technical Skills

- Password-security testing
- Hash extraction and handling
- John the Ripper
- Johnny GUI
- Networkwalks security tools
- Protected-file analysis
- Controlled security testing
- Evidence collection
- Technical documentation
- Security workflow analysis

---

# 🛡️  Observations & Technical Considerations

##  Observation 01 Hash Format

The PDF hash must be preserved correctly before being supplied to the password-recovery tool.

The `$pdf$` prefix is an important indicator of the PDF hash format used during the practical.

---

##  Observation 02 Recovery Time

Password-recovery duration can vary depending on:

- Password complexity
- Search space
- Attack configuration
- Hardware capabilities
- Processing performance

A simple password may be recovered significantly faster than a complex password with a large candidate space.

---

##  Observation 03 Evidence Matters

The practical demonstrated that cybersecurity work is not limited to running tools.

A professional assessment should also demonstrate:

```text
What was performed
        ↓
How it was performed
        ↓
What was observed
        ↓
What evidence supports the observation
        ↓
What the observation means
```

This makes the work reproducible, reviewable, and professionally documented.

---

##  Observation 04 Password Strength

The practical reinforces the importance of strong passwords.

Weak or predictable passwords may be significantly easier to recover during password-security testing.

Organizations and users should therefore use strong, unique credentials and appropriate authentication controls.

---

# 🛡️  Risk Analysis & Impact

| **#** | 🔎 **Observation** | 📊 **Security Relevance** | ⚠️ **Potential Impact** | **Risk** |
|---:|---|---|---|---|
| 1 | Weak password discovered during authorized recovery exercise | Demonstrates password predictability | Unauthorized access may become easier if similar credentials are used in real systems | 🟠 **Medium** |
| 2 | Password hash available for testing | Hashes can become targets for offline password analysis | Weak passwords may be recovered from compromised hashes | 🟠 **Medium** |
| 3 | Protected file relies on password-based protection | Security depends partly on password strength | Weak credentials may reduce protection effectiveness | 🟠 **Medium** |
| 4 | Password-recovery tools can automate candidate testing | Demonstrates the importance of password resilience | Weak credentials may be recovered more efficiently | 🟠 **Medium** |
| 5 | Hash handling requires accuracy | Incorrect or incomplete hashes may cause recovery workflows to fail | Operational errors during security testing | 🟢 **Low** |

> **Important Assessment Note:**
>
> These observations are based on an **authorized educational laboratory exercise**. They should not be interpreted as vulnerabilities in unrelated production systems.

---

# 🛡️  Recommendations

### 1️⃣ Use Strong Passwords

Passwords should be long, unique, and difficult to predict.

### 2️⃣ Avoid Password Reuse

Users should avoid reusing the same password across multiple systems or services.

### 3️⃣ Use Password Managers

Password managers can assist users in generating and securely storing unique credentials.

### 4️⃣ Implement Multi-Factor Authentication

Where supported, MFA should be enabled to provide an additional authentication layer beyond passwords.

### 5️⃣ Protect Password Hashes

Organizations should securely store password-related data and prevent unauthorized access to credential databases.

### 6️⃣ Use Modern Password-Storage Mechanisms

Production systems should use appropriate password hashing and key-stretching mechanisms rather than storing passwords directly.

### 7️⃣ Perform Authorized Password Audits

Organizations should periodically evaluate password security through authorized security assessments.

### 8️⃣ Monitor Credential Exposure

Organizations should monitor for exposed credentials and take appropriate action when compromise is suspected.

### 9️⃣ Document Security Testing

Security assessments should maintain clear evidence of scope, procedures, observations, and results.

### 🔟 Maintain Authorization

Password-security testing must always be conducted within a clearly defined and authorized scope.

---

# 🛡️ Security Assessment Summary

| **Assessment Area** | **Status** |
|---|---|
| Password Security Fundamentals | ✅ Completed |
| PDF Hash Extraction | ✅ Completed |
| John the Ripper Exercise | ✅ Completed |
| Johnny Configuration | ✅ Completed |
| Networkwalks Hash Calculator | ✅ Completed |
| Networkwalks Password Cracker | ✅ Completed |
| Password Verification | ✅ Completed |
| Evidence Collection | ✅ Completed |
| Technical Documentation | ✅ Completed |
| Authorized Laboratory Testing | ✅ Completed |

### Overall Practical Progress

```text
PASSWORD SECURITY       ████████████████████ 100%  COMPLETED ✅
HASH EXTRACTION         ████████████████████ 100%  COMPLETED ✅
JTR / JOHNNY             ████████████████████ 100%  COMPLETED ✅
NETWORKWALKS TOOLS       ████████████████████ 100%  COMPLETED ✅
PASSWORD VERIFICATION    ████████████████████ 100%  COMPLETED ✅
DOCUMENTATION            ████████████████████ 100%  COMPLETED ✅
```

---

# 🛡️  Key Learning Outcomes

Through the Week 3 practical exercises, I developed hands-on experience with:

- Password-security concepts
- Hash analysis
- Protected-file analysis
- John the Ripper
- Johnny GUI
- Networkwalks security tools
- PDF hash extraction
- Password recovery workflows
- Evidence collection
- Professional technical documentation
- Authorized security-testing principles

The exercises demonstrated how password-security testing can be approached through different tools while following a consistent security-testing methodology.

The practical also reinforced that **technical execution and professional documentation are equally important** in cybersecurity.

---

### 🛡️ Learning Validation

The assessment provided an opportunity to validate theoretical understanding alongside the practical laboratory exercises.

```text
KNOWLEDGE
    ↓
PRACTICAL LAB
    ↓
EVIDENCE
    ↓
DOCUMENTATION
    ↓
SECURITY UNDERSTANDING
```

---

# 🛡️  Conclusion

During **Week 3 of my Cybersecurity & Ethical Hacking internship at Networkwalks Academy**, I completed practical exercises focused on **password security, hash analysis, password recovery, and protected-file security testing**.

The first module provided hands-on experience with **John the Ripper and Johnny**, including PDF hash extraction, hash-file preparation, password recovery, and verification.

The second module provided practical experience with the **Networkwalks Hash Calculator and Password Cracker**, demonstrating a browser-based approach to the same general password-security workflow.

The practical reinforced several important cybersecurity principles:

```text
PASSWORD SECURITY
        ↓
HASH ANALYSIS
        ↓
AUTHORIZED TESTING
        ↓
PASSWORD RECOVERY
        ↓
VERIFICATION
        ↓
EVIDENCE
        ↓
PROFESSIONAL DOCUMENTATION
```

I also learned that effective cybersecurity work involves more than simply operating security tools.

A professional security practitioner must understand:

```text
What was performed
        ↓
Why it was performed
        ↓
What was discovered
        ↓
What the evidence demonstrates
        ↓
What security lesson can be learned
        ↓
How the risk can be reduced
```

Most importantly, the practical reinforced the requirement that password-recovery and security-testing techniques must only be used within an **authorized scope**.

This project represents another step in my development as a cybersecurity professional and contributes to my practical experience in **ethical hacking, password security, security tooling, evidence collection, and technical documentation**.

---

# 🛡️  Project Information

| **Project Detail** | **Information** |
|---|---|
| 👤 **Author** | **Josiah Ayuba** |
| 🏢 **Program** | Cybersecurity Program Networkwalks |
| 📅 **Week** | **Week 03** |
| 🎓 **Batch** | **B083** |
| 📆 **Assessment Submission** | **25 September 2026** |
| 🔐 **Project Type** | Authorized Cybersecurity Laboratory |
| 🛡️ **Primary Focus** | Password Security & Cracking |
| ⚔️ **Module 01** | John the Ripper & Johnny |
| 🌐 **Module 02** | Networkwalks Hash Calculator & Password Cracker |
| 💻 **Primary Platform** | Windows |
| 📄 **Target** | Authorized Protected PDF |
| #️⃣ **Hash Type** | PDF Hash |
| 📸 **Evidence** | Screenshots |
| 📊 **Assessment Status** | Completed |

---

# 👤  Author

<div align="center">

### **Josiah Ayuba**

**Cybersecurity Professional | Networkwalks Intern | Batch B083**

<br>
