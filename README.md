# Password-Cracking-with-John-the-Ripper-and-Networkwalks-tools-Week-3-Project-Task-Lab-
A hands-on internship project covering password recovery of a protected PDF file using two different approaches: John the Ripper (JTR), and the Networkwalks online Hash Calculator &amp; Password Cracker tools.

![Skill](https://img.shields.io/badge/Skill-Cybersecurity-red) ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-2026.2-orange) ![John the Ripper](https://img.shields.io/badge/John%20the%20Ripper-JTR-blue) ![Johnny](https://img.shields.io/badge/Johnny-GUI-lightgrey) ![Networkwalks Tools](https://img.shields.io/badge/Networkwalks-Tools-lightgrey) ![Skill](https://img.shields.io/badge/Skill-Password%20Cracking-red) ![Skill](https://img.shields.io/badge/Skill-Hash%20Extraction-red) ![Ethical Hacking](https://img.shields.io/badge/Ethical-Hacking-orange) ![Networkwalks](https://img.shields.io/badge/Networkwalks-grey) ![Author](https://img.shields.io/badge/Author-Salifu%20Isaiah-red)


## 📌 About This Project

This project documents two practical exercises completed during Week 3 of my Cybersecurity internship at Networkwalks: cracking the password of a protected PDF file (`My Locked PDF1.pdf`) using two different methods — John the Ripper via command line in Kali Linux, and the Networkwalks Hash Calculator & Password Cracker web tools.

Both exercises target the same locked PDF, so together they compare a local offline cracking tool against a browser-based online cracking tool, showing two valid approaches to the same recovery task.

## 🛡️ Liability Disclaimer

I carried out these activities only on a file provided for training purposes as part of my Networkwalks Cybersecurity internship. These materials are for educational purposes only. I understand that unauthorized access or misuse of these techniques against files or systems I do not own or have permission to test is illegal, and that every action taken with this knowledge is my own responsibility.


# 🛡️ 4. Tools & Technologies

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
## 5.  Practical Procedure

### 🔹 5.1 Obtain John the Ripper

John the Ripper was obtained for the Windows environment as required for the laboratory exercise.

---

### 🔹 5.2 Configure Johnny

Johnny GUI was configured to work with the John the Ripper installation.

The `john.exe` executable was selected from the appropriate JTR `run` directory.

---

### 🔹 5.3 Obtain the Protected PDF

The protected PDF supplied for the cybersecurity practical was used as the authorized laboratory target.

---

### 🔹 5.4 Extract the PDF Hash

The protected PDF was processed to obtain its corresponding password hash.

The resulting hash followed the expected PDF hash format beginning with:

```text
$pdf$
```

---

### 🔹 5.5 Create the Hash File

The extracted hash was saved into a text file:

```text
hash1.txt
```

The hash was preserved as required so that it could be loaded into Johnny.

---

### 🔹 5.6 Load the Hash into Johnny

The saved hash file was loaded through Johnny using the password-file workflow.

This provided JTR with the required hash input for the laboratory exercise.

---

### 🔹 5.7 Start Password Recovery

A password-recovery process was initiated through Johnny.

The recovery process demonstrated how password-security tools can test candidate passwords against a supplied password hash.

Recovery time can vary depending on factors such as:

- Password complexity
- Candidate search space
- System performance
- Available processing resources
- Attack configuration

---

### 🔹 5.8 Verify the Recovered Password

The recovered password was used to open the protected PDF.

Successful opening of the PDF provided verification that the password-recovery process had produced the expected result.

---
### 🔹 Screenshot Evidence Using JTR

