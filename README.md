# AWS Cloud Security Lab - S3 Bucket Access Control

## Overview
This project demonstrates secure configuration and access control for an Amazon S3 bucket.  
The goal is to understand and implement AWS best practices for **restricting public access** to cloud storage resources.

## Objectives
- Create a secure S3 bucket in AWS.
- Upload test files to the bucket.
- Configure **Block Public Access** settings to ensure private data remains inaccessible to the public.
- Verify bucket security using AWS Console permissions view.

## Steps Performed
1. **Created an S3 Bucket**  
   - Name: `ben-cloud-security-lab`  
   - Region: **US East (Ohio) (us-east-2)**  
   - Bucket type: **General purpose**

2. **Uploaded a Test File**  
   - File used: `test.txt` (or any small file for verification)

3. **Configured Security Settings**  
   - Enabled **Block all public access** (all four checkboxes)
   - Verified permissions to ensure no public access allowed.

4. **Verification**  
   - Checked the bucket and object permissions in AWS Console.
   - Confirmed the bucket is private and inaccessible from the public internet.

## Skills Demonstrated
- AWS S3 bucket creation and configuration
- Cloud storage security principles
- Access control management
- Understanding AWS console navigation

## Tools & Services Used
- **Amazon S3** (Simple Storage Service)
- AWS Console

## Next Steps / Improvements
- Implement S3 bucket policies for fine-grained permissions.
- Use AWS CLI to manage and audit bucket configurations.
- Add logging and monitoring using AWS CloudTrail.

---

**Author:** Ben Emanuel  
**GitHub:** [Benemanuel05](https://github.com/Benemanuel05)  
**LinkedIn:** [Ben Emanue](https://www.linkedin.com/in/emanuel05/)  
**Email:** Benyouareben@gmail.com
