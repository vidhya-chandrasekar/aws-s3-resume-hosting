# AWS S3 Resume Hosting Project
## Overview
This project demonstrates hosting a personal resume as a static website using **Amazon S3**. It showcases practical knowledge of AWS services, static website hosting, bucket policies, and troubleshooting common issues.  

**Live Resume URL (S3 Website Endpoint):**  
http://vidhyashreeresumeaws.s3-website-us-west-2.amazonaws.com 

---

## Tools & Services Used
- **AWS S3**: Storage and static website hosting  
- **AWS IAM**: Permissions and access control  
- **Web Browser**: Testing hosted resume  

---

## Project Highlights
- Uploaded `VIDHYASHREE RESUME AWS.pdf` to S3 bucket.  
- Configured **bucket policy** to allow public read access.  
- Enabled **Static Website Hosting** with correct index document.  
- Documented **step-by-step screenshots** and common errors.  
- Hosted resume accessible via public URL.  

---

## Errors Encountered & Solutions
1. **403 Forbidden**
   - Cause: Bucket not publicly accessible  
   - Solution: Disabled *Block Public Access* and added bucket policy for `s3:GetObject`  

2. **“Make public (ACL)” option disabled**
   - Cause: AWS console now disables ACLs by default  
   - Solution: Used bucket policy to make objects public  

3. **Filename case/space sensitivity**
   - Cause: Static website index document did not match exact file name  
   - Solution: Renamed file to `resume.pdf` or used exact filename in settings  

---

## Files in Repo
- `AWS-S3-Resume-Hosting.pdf` → Full screenshot-based project report  
- `README.md` → Project summary  

---

## Conclusion
This project demonstrates the **practical deployment of a static website on AWS S3**, handling permissions, hosting, and troubleshooting. It’s an example of applying cloud concepts for real-world use cases.  

---

