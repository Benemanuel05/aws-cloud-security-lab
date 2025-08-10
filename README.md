# AWS Cloud Security Lab

This lab demonstrates how to set up and secure an AWS S3 bucket to prevent unauthorized access, following cloud security best practices.

---

## **Lab Overview**
- **Service Used:** Amazon S3 (Simple Storage Service)
- **Region:** US East (Ohio) us-east-2
- **Goal:** Create a secure bucket, configure permissions, test access controls, and verify security settings.
- **Skills Learned:**
  - AWS S3 bucket creation and configuration
  - Setting bucket policies for least privilege
  - Understanding and testing access permissions
  - Using AWS Management Console effectively

---

## **Step-by-Step Process**

### 1. S3 Overview
Created a new S3 bucket named `ben-cloud-security-lab` with default security settings and **Bucket Owner Enforced** enabled for object ownership.

![S3 Overview](s3_overview.png)

---

### 2. Bucket Permissions
Configured the bucket to follow **least privilege** principles, ensuring no public access was allowed.

![Bucket Permissions](bucket_permissions.png)

---

### 3. Testing Access Restrictions
Verified that unauthorized access attempts resulted in an **Access Denied** error.

![Access Denied](access_denied.png)

---

### 4. File Upload Verification
Uploaded a test file to confirm correct permissions and bucket functionality.

![Test File Uploaded](test_file_uploaded.png)

---

## **Security Takeaways**
- Always enable **Bucket Owner Enforced** to maintain control over uploaded objects.
- Public access should be blocked unless explicitly required.
- Test permissions after configuration to verify that security policies work as intended.
- Store sensitive or private data only in buckets with strict access policies.

---

## **Next Steps**
- Implement S3 server-side encryption.
- Set up AWS CloudTrail logs for monitoring access attempts.
- Create an automated alert system for policy changes.

---

**Author:** Ben Emanuel  
**Date:** August 2025
//github.com/Benemanuel05)  
**LinkedIn:** [Ben Emanue](https://www.linkedin.com/in/emanuel05/)  
**Email:** Benyouareben@gmail.com
