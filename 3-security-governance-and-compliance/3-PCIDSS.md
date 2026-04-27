## 🔐 Payment Card Industry Data Security Standard (PCI DSS)

---

### 📘 Concept

The **Payment Card Industry Data Security Standard (PCI DSS)** is a **contractual security standard**, not a law or government regulation.

- Enforced by **payment card brands**  
- Applies to any organization that **stores, processes, or transmits cardholder data**  

The objective is to **protect cardholder data and reduce payment fraud** within the cardholder data environment (CDE).

---

### 🧩 Control Framework (12 Requirements → 6 Objectives)

**1. Build and Maintain a Secure Network and Systems**  
- Install and maintain **firewalls** to protect cardholder data  
- Do not use **vendor default passwords or settings**

**2. Protect Cardholder Data**  
- Protect **stored cardholder data**  
- Encrypt transmission across **open or public networks**

**3. Maintain a Vulnerability Management Program**  
- Protect systems against **malware**  
- Develop and maintain **secure systems and applications**

**4. Implement Strong Access Control Measures**  
- Restrict access based on **business need to know**  
- **Identify and authenticate** users and systems

**5. Regularly Monitor and Test Networks**  
- **Track and monitor** access to network resources and cardholder data  
- **Test security systems and processes** regularly

**6. Maintain an Information Security Policy**  
- Maintain a policy addressing **security for all personnel**

---

<p align="center">
  <img src="assets/PCI-DSS.png" alt="PCI DSS Control Objectives and Requirements" width="800">
</p>

---

### ⚠️ Critical Principle

PCI DSS is **scope-specific and contractually enforced**.

<p align="center"><strong>Cardholder Data Environment (CDE) Only → Contractual Obligation</strong></p>

Controls apply **only to systems that handle cardholder data**, not the entire enterprise.

---

### 🎯 Why This Matters (CISSP Context)

Falls under **Security and Risk Management (Domain 1)** and represents **contractual and financial risk**, not regulatory law.

Non-compliance can result in:

- Financial penalties and fines  
- Increased transaction fees  
- Loss of ability to process payment cards  
- Direct business disruption  

CISSP questions will test your ability to:

- Recognize PCI DSS as **contractual**  
- Apply controls to the **correct scope (CDE)**  
- Prioritize **segmentation, access control, and monitoring**

---

### 🧠 CISSP Decision Lens

When evaluating a scenario:

- Does the system handle **cardholder data**? → PCI applies  
- Is the requirement **contractually enforced**? → Yes  
- Can scope be **reduced through segmentation**? → Always preferred  

Default mindset:

**Limit scope, protect the CDE, enforce strong controls**

---

### 🚨 Exam Trap

- Treating PCI DSS as a **law or regulation**  
- Applying PCI requirements **outside the cardholder data environment**  
- Ignoring **segmentation to reduce scope**

---

### ✅ Exam Takeaway

**PCI DSS is contractual, not legal.**

- Applies only to **cardholder data environments**  
- Enforces **12 core security requirements**  
- Focuses on **fraud prevention and data protection**

---

### 📚 Authoritative References

- PCI Security Standards Council – PCI DSS v4.0  
- NIST SP 800-53 – SC (System and Communications Protection), AC (Access Control), SI (System Integrity)  
- NIST SP 800-41 – Guidelines on Firewalls and Boundary Protection  
- ISO/IEC 27001 – Information Security Management Systems
