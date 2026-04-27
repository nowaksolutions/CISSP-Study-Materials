## 🔐 Onboarding and Offboarding Processes

---

### 📘 Concept

Personnel access must be controlled across the **entire employment lifecycle**.

The objective is to **grant only necessary access when employment begins** and **immediately revoke all access when it ends**.

---

### 🧩 Onboarding (Access Provisioning)

**Security Awareness and Training**  
Provide **initial security training** to establish expected behavior and risk awareness.

**Policy Acknowledgment**  
Require formal acknowledgment of **policies, standards, and acceptable use**.

**Access Provisioning**  
Grant access based on:

- **Least Privilege**  
- **Need to Know**  
- **Role-based requirements**  

Access should be **approved, documented, and traceable**.

---

### 🧩 Offboarding (Access Deprovisioning)

**Formal Termination Process**  
Follow a **defined termination policy** with proper coordination between HR and IT.

**Immediate Access Revocation**  
Revoke **all logical and physical access immediately upon termination**.

**Asset Recovery**  
Collect all **company-owned devices, credentials, and materials**.

**Credential and Password Updates**  
Change **shared passwords, service accounts, and administrative credentials**.

**Controlled Termination (Best Practice)**  
Conduct termination with **multiple representatives present** to ensure proper handling and reduce risk.

---

### ⚠️ Critical Principle

**Access must be tightly controlled at entry and immediately removed at exit.**

<p align="center"><strong>Provision Carefully → Revoke Immediately</strong></p>

---

### 🎯 Why This Matters (CISSP Context)

Spans **Identity and Access Management (Domain 5)** and **Security Operations (Domain 7)**.

Improper lifecycle management leads to:

- Unauthorized access after termination  
- Insider threats and sabotage  
- Data exfiltration risks  
- Orphaned or unmanaged accounts  

CISSP questions will often expect **immediate access revocation** as the correct answer in termination scenarios.

---

### 🧠 CISSP Decision Lens

When evaluating a scenario:

- Is access being **granted appropriately at onboarding**?  
- Is access **limited to role and necessity**?  
- Has access been **revoked immediately upon termination**?  

Default mindset:

**Access granted with control → Access removed without delay**

---

### 🚨 Exam Trap

Delaying **access revocation after termination**, even briefly.

---

### ✅ Exam Takeaway

**Immediate access revocation is critical during offboarding.**

---

### 📚 Authoritative References

- NIST SP 800-53 – AC (Access Control) and PS (Personnel Security) Control Families  
- NIST SP 800-12 – Access Control and Personnel Lifecycle Management  
- NIST SP 800-61 – Incident Handling (insider threat considerations)  
- ISO/IEC 27001 – Access Control and Human Resource Security
