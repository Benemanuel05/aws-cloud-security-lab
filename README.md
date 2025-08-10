# AWS Cloud Security Lab

This short lab demonstrates how to set up and secure an Amazon S3 bucket to prevent unauthorized access, following cloud security best practices.

---

## Lab Overview
- **Service:** Amazon S3 (Simple Storage Service)  
- **Region:** US East (Ohio) — `us-east-2`  
- **Goal:** Create a secure bucket, configure access control, upload test objects, and verify that unauthorized access is denied.

---

## Step-by-step summary

### 1) S3 Overview
Created a new S3 bucket named `ben-cloud-security-lab`.

![S3 Overview](Screenshots/s3_overview.png)
*Bucket list showing the `ben-cloud-security-lab` bucket.*

---

### 2) Bucket Permissions — Block Public Access
Confirmed **Block public access** settings are enabled to prevent public exposure.

![Bucket Permissions](Screenshots/bucket_permissions.png)
*Block public access settings to enforce least privilege.*

---

### 3) Upload & Test Object Access
Uploaded a test file and verified unauthorized requests return **Access Denied**.

![Test File Uploaded](Screenshots/test_file_uploaded.png)
*Uploaded test file listed in the bucket.*

![Access Denied](Screenshots/access_denied.png)
*Access Denied shown in an incognito window — verifies the object is private.*

---

## Security takeaways
- **Always enable Block Public Access** unless you have an explicit reason otherwise.  
- Test object URLs in an incognito window to ensure they are private.  
- Consider enabling **SSE (server-side encryption)** and **CloudTrail** for auditing and retention.  
- Use IAM least-privilege policies for users and roles rather than broad bucket policies.

---

## Next steps (optional)
- Add SSE-KMS server-side encryption.
- Configure CloudTrail and S3 access logging.
- Add a role and a policy to demonstrate least-privilege access via IAM.

---

**Author:** Ben Emanuel  
**Date:** August 2025  
**GitHub:** https://github.com/Benemanuel05
