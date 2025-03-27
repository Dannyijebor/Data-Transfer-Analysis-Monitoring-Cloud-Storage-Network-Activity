---

# **Cloud Data Monitoring & Security Analysis**  
📊 **Detecting Anomalies in Cloud Storage & Network Activity**  

## **🚀 Project Overview**  
This repository provides an **in-depth analysis of cloud storage usage, data transfer patterns, and security risks**. By examining **cloud application activities**, we can detect **potential data leaks, security vulnerabilities, and unauthorized access**.  

### **🔍 Key Objectives:**  
✅ Identify **top applications consuming bandwidth**  
✅ Detect **suspicious upload/download trends**  
✅ Enhance **data security with monitoring strategies**  
✅ Provide **step-by-step solutions to mitigate risks**  

---

## **📈 Data Insights from the Dashboard**  

### **1️⃣ High-Volume Cloud Storage Usage**  
The **top applications by data transfer** include:  
- **Google Drive (35.72 GB total, 34.01 GB uploaded)** – 🚨 Large file uploads could indicate **data migration or potential exfiltration**  
- **Microsoft OneDrive & Office 365 OneDrive (8.17 GB total)** – Heavy corporate file storage use  
- **Dropbox (230.63 GB total)** – Primarily used for **retrieving files** rather than uploading  

🛑 **Why this matters:**  
- **Large uploads** may indicate **unauthorized data transfers or backups**  
- **Mass downloads** could mean **sensitive files are being exfiltrated**  

---

### **2️⃣ Application & User Activity Breakdown**  
Cloud storage apps were **used in different ways**, such as:  
- **Amazon S3 Control** – Mainly **viewing** activity  
- **WeTransfer & Filemail** – Frequent **uploading & sharing**, which may suggest **data being sent externally**  
- **iCloud Drive & GCP Storage** – High **download frequency**, signaling **possible mass data retrieval**  

🛑 **Why this matters:**  
- External file-sharing apps (**WeTransfer, Filemail**) **bypass company security policies**  
- High download rates from **personal storage accounts** could mean **insider data theft risks**  

---

### **3️⃣ Event Activity Breakdown**  
The **most common actions recorded**:  
- **Edit (11,475 events)** – Frequent document modifications  
- **Download (5,031 events)** – Large file retrieval activity  
- **Upload (1,291 events)** – Data movement into the cloud  

🛑 **Why this matters:**  
- **Mass downloads** might indicate a **security breach or pre-exfiltration activity**  
- **Editing activity** suggests **collaborative work but could also mask data manipulation attempts**  
- **Uploads should be restricted** to prevent **leakage of sensitive information**  

---

## **🔧 Step-by-Step Guide: Investigating & Securing Cloud Data Transfers**  

### **🛠️ Step 1: Identify High-Risk Applications**  
1️⃣ Use **cloud security tools** (Microsoft Defender for Cloud Apps, AWS GuardDuty, Google Security Center)  
2️⃣ Audit applications with **high upload/download activity**  
3️⃣ Identify if employees are **using unauthorized cloud storage services**  

---

### **🧐 Step 2: Detect Anomalous Behavior**  
1️⃣ **Enable logging & auditing** for all cloud platforms  
2️⃣ **Create alerts** for:  
   - Large **data uploads to external storage**  
   - **Mass downloads** of company files  
   - **Unauthorized sharing** via public links  
3️⃣ Use **SIEM (Security Information & Event Management) systems** to detect risks  

---

### **🔒 Step 3: Strengthen Security Controls**  
✔️ **Set Data Loss Prevention (DLP) policies** to restrict uploads  
✔️ **Enforce Multi-Factor Authentication (MFA) for cloud access**  
✔️ **Block unauthorized file-sharing applications**  
✔️ **Encrypt sensitive documents before storing them in the cloud**  

---

## **📌 Why This Repository?**  
✅ **Educational Resource:** Learn how to **analyze & secure cloud data transfers**  
✅ **Step-by-Step Security Strategies:** Easy-to-follow **guides to improve security**  
✅ **Best Practices for IT & Cybersecurity Teams**  

💡 **Want to contribute?** Submit a **Pull Request** with additional security insights!  

---
