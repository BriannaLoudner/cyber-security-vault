# 🖥️ Cybersecurity & Health IT Lab Notes  
**Author:** Brianna Loudner  
**Purpose:** Document raw research, technical outputs, and reflections from completed labs  
**Audience:** Students, healthcare staff, and anyone learning cybersecurity basics  

## 🔐 Password Security Lab
**Objective:** Evaluate personal password habits and apply best practices.  
**Definitions:**
  1. **Hashing:** A one-way transformation of data used to store passwords securely.  
     - *Example:* SHA-256("password123") → ef92b778bafe771e89245b89ecbc08a44a4e166c06659911881f383d4473e94f  
2. **Salting:** Adding random data to a password before hashing to prevent dictionary and rainbow table attacks.  
     - *Example:* random123 + password123 → unique hash  
3. **Password Manager:** A tool that stores and encrypts passwords, helping users create strong, unique credentials for each account.  
     - *Example:* Bitwarden, 1Password, KeePass     
### 🤯 Key Learnings  
- Weak passwords are vulnerable to dictionary attacks.  
- Password managers reduce reuse and improve complexity.  
- Salting makes hashes more secure and harder to reverse-engineer.  
### 📝 Notes-to-Self  
-  Review hash formats (MD5 vs SHA-256 vs bcrypt)  
-  Add visual comparison of password strength in future training materials  
-  Explore how password managers handle encryption and syncing  

## Malware Analysis Report
**Objective:** Identify types of malware and their impact on healthcare systems.
**Definitions:**  
1. *Malware:* Malicious software designed to disrupt, damage, or gain unauthorized access to systems.  
   - Types include: viruses, worms, trojans, ransomware, and spyware.  
2. *Ransomware:* Malware that encrypts files and demands payment for decryption.  
   - Example: WannaCry attack on NHS (2017)  
3. *Trojan Horse:* Malware disguised as legitimate software to trick users into installing it.  
   - Example: Fake medical billing software that installs keyloggers  
4. *Payload vs Delivery Method:*  
   - *Payload:* The actual malicious action (e.g., encryption, data theft)  
   - *Delivery Method:* How the malware reaches the system (e.g., phishing email, USB drive)  
### 📸 **Screenshots**
<img width="696" height="351" alt="Screenshot 2025-09-14 165701" src="https://github.com/user-attachments/assets/47f2ee0f-1d2e-462d-a1a6-7c5113e71be4" />  
<img width="1653" height="536" alt="Screenshot 2025-09-04 202849" src="https://github.com/user-attachments/assets/dba81478-2f2c-4d8a-9d00-f24603cbae93" />  

### ✅ Key Learnings  
  - Healthcare systems are vulnerable due to outdated software and limited staff training.
- Trojans often exploit trust in medical tools or billing systems.
- Ransomware can halt operations and compromise patient safety.
### 📝 Notes-to-Self
-  Clarify the difference between payload and delivery method in training slides
-  Add a flowchart of malware lifecycle for visual learners
-  Research common malware entry points in clinical environments

## Ransomware Case Study  
### 🎯 Objective: Analyze a real-world ransomware incident and propose mitigation strategies.  
### 🧾 Case Summary  
- **Target:** Small clinic with outdated systems  
- *Entry Point:* Phishing email with malicious attachment  
- ***Impact:*** Patient records inaccessible for 3 days; staff resorted to paper charts
### 🛡️ Mitigation Strategies  
- Regular backups (offline and encrypted)  
- Staff training on email safety and phishing detection  
- Patch management system to keep software up to date  
- Incident response plan with clear roles and recovery steps  
### ✅ Key Learnings  
- Human error (clicking on malicious links) is a major vulnerability  
- Backup frequency and storage method directly affect recovery time  
- Clinics need simple, printable checklists for emergency response  
### 📝 Notes-to-Self  
-  Research how backup frequency affects recovery time  
-  Create a printable “incident response checklist” for future training  
-  Explore open-source tools for ransomware detection and prevention  
