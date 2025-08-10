# **AWS Cloud Security Lab**

This lab demonstrates how to securely configure an Amazon S3 bucket to prevent unauthorized access, following AWS cloud security best practices.

---

## **Lab Overview**
- **Service Used:** Amazon S3 (Simple Storage Service)  
- **Region:** US East (Ohio) `us-east-2`  
- **Goal:** Create a secure bucket, configure permissions, test access controls, and verify security settings.  
- **Skills Learned:**  
  - S3 bucket creation and configuration  
  - Applying least privilege permissions via bucket policies  
  - Testing access controls for security verification  
  - Using AWS Management Console effectively  

---

## **Project Purpose**
The purpose of this lab is to demonstrate practical AWS S3 security implementation, showcasing my ability to configure cloud resources following **industry best practices**.  
This project simulates a real-world task a cloud security engineer might face when setting up secure data storage in the cloud.

---

## **Technologies Used**
- **AWS S3** — Cloud storage service  
- **AWS Management Console** — For bucket creation and permissions setup  
- **IAM Policies** — To control access to the bucket  
- **Local Machine** — For test file creation and uploads  

---

## **Step-by-Step Process**

### **1. S3 Overview**
Created a new S3 bucket named `ben-cloud-security-lab` with default security settings and **Bucket Owner Enforced** enabled for object ownership.  

![S3 Overview](Screenshots/s3_overview.png)  

---

### **2. Bucket Permissions**
Configured the bucket to follow **least privilege** principles, ensuring **no public access** was allowed.  

![Bucket Permissions](Screenshots/bucket_permissions.png)  

---

### **3. Testing Access Restrictions**
Verified that unauthorized access attempts resulted in an **Access Denied** error.  

![Access Denied](Screenshots/access_denied.png)  

---

### **4. File Upload Verification**
Uploaded a test file to confirm correct permissions and bucket functionality.  

![Test File Uploaded](Screenshots/test_file_uploaded.png)  

---

## **Security Takeaways**
- Always enable **Bucket Owner Enforced** to maintain control over uploaded objects.  
- Public access should remain **blocked** unless explicitly required.  
- Test permissions after configuration to verify that security policies work as intended.  
- Store sensitive or private data only in buckets with strict access policies.  

---

## **Next Steps**
- Implement **S3 server-side encryption** for data at rest.  
- Set up **AWS CloudTrail** to monitor access attempts.  
- Configure **automated alerts** for bucket policy changes.  

---

**Author:** Ben Emanuel  
**Date:** August 2025  
**GitHub:** [Benemanuel05](https://github.com/Benemanuel05)  
**LinkedIn:** [Ben Emanue](https://www.linkedin.com/in/emanuel05/)  
**Email:** Benyouareben@gmail.com  
