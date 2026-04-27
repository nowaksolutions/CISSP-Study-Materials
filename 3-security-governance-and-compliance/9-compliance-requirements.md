<h1 align="center">🧭 Determining Compliance Requirements</h1>
<p align="center"><strong>Scope • Jurisdiction • Data Type • Control Mapping</strong></p>

---

## 📘 Concept

Determining compliance requirements means identifying and adhering to **all applicable**:

- Laws  
- Regulations  
- Standards  
- Contractual obligations  

that govern how an organization protects **data, systems, and operations**.

These requirements vary by **industry, geography, and data type** and often **overlap**.

---

## 🧩 Core Frameworks and Laws (Quick Scope)

**CFAA (Computer Fraud and Abuse Act)**  
> Unauthorized access and computer-related fraud

**Privacy Act of 1974**  
> U.S. federal agencies handling personal data

**Computer Security Act of 1987**  
> Federal security policies and training for sensitive systems

**FISMA**  
> Risk-based security programs and **continuous monitoring** for federal systems

**EEA (Economic Espionage Act)**  
> Theft or misappropriation of **trade secrets**, including foreign actors

**USA PATRIOT Act**  
> Expanded **government surveillance and data access** authority

**SOX (Sarbanes-Oxley Act)**  
> Financial reporting integrity and **internal controls** for public companies

**PCI DSS (Contractual, NOT Law)**  
> Protection of **cardholder data**

**GLBA**  
> Protection of **customer financial information**

**Basel II Accords**  
> International banking **risk management and capital requirements**

**HIPAA**  
> Protection of **PHI (health data)**

**PIPEDA (Canada)**  
> Commercial **personal data protection**

**GDPR (EU)**  
> Personal data protection with **strong user rights and extraterritorial scope**

---

## ⚠️ Critical Principle

Compliance is **not singular**. It is **layered and overlapping**.

<p align="center"><strong>Multiple Laws → Shared Controls → Unified Compliance</strong></p>

You must satisfy **all applicable requirements simultaneously**.

---

## 🎯 Why This Matters (CISSP Context)

Falls under **Security and Risk Management (Domain 1)** and represents:

- Regulatory risk  
- Legal liability  
- Operational and reputational risk  

Failure leads to:

- Fines and penalties  
- Legal enforcement  
- Operational restrictions  
- Loss of business trust  

CISSP questions will test your ability to:

- Identify **which laws apply**  
- Recognize **overlapping requirements**  
- Select controls that **satisfy multiple frameworks**

---

## 🧠 CISSP Decision Lens

Evaluate every scenario using this sequence:

1. **Data Type**  
   - Financial → GLBA / PCI DSS  
   - Health → HIPAA  
   - Personal → GDPR / PIPEDA  

2. **Industry**  
   - Banking → GLBA / Basel II  
   - Healthcare → HIPAA  
   - Public sector → FISMA  

3. **Jurisdiction**  
   - U.S. → Federal laws  
   - EU → GDPR  
   - Canada → PIPEDA  
   - Global → Multiple overlapping requirements  

4. **Control Mapping**  
   - Align controls to **ALL applicable laws**  
   - Default to the **strictest requirement**

<p align="center"><strong>Data → Industry → Jurisdiction → Controls</strong></p>

---

## ⚙️ Key Strategy

**Implement controls once, satisfy many requirements.**

Examples:
- Access control → supports HIPAA, GLBA, PCI DSS  
- Encryption → supports GDPR, PCI DSS, PIPEDA  
- Logging and monitoring → supports FISMA, SOX, PCI DSS  

---

## 🚨 Exam Trap

- Assuming **only one regulation applies**  
- Ignoring **jurisdictional overlap**  
- Treating **PCI DSS as a law** instead of contractual  

---

## ✅ Exam Takeaway

**Compliance is determined by:**

- Data type  
- Industry  
- Jurisdiction  

**Always map controls to ALL applicable requirements and meet the strictest one.**

---

## 📚 Authoritative References

- NIST SP 800-53 – Security and Privacy Controls  
- NIST SP 800-37 – Risk Management Framework  
- NIST SP 800-39 – Enterprise Risk Management  
- ISO/IEC 27001 – Information Security Management Systems  
- GDPR (EU 2016/679), HIPAA, GLBA, SOX, PIPEDA
