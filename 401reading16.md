*Juan Miguel Cano*
*January 29, 2024*

# Readings: Cloud Identity and Access Management (IAM) with AWS

## Reading 16
[Lessons Learned from the Capital One Data Breach (PDF)](https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf)


**What were the three commands used for the attack?**
- Get Credentials: First command, when executed, obtained security credentials known as ***-WAF-Role account (an IAM account ) for an elevated role access AWS Web Application Firewall (WAF)
- List Buckets: Second command, when executed, used the security credentials ****-WAR-Role account to list files and folders (aka S3 buckets)
- Download Files: Third command, when executed, used the ****_WAF-Role account to download files that were accessible by the credentials.

**What misconfiguration of AWS components allowed the attacker to access sensitive data?**
- The attack occurred due to a misconfiguration error at the application layer of a firewall installed by the Financial Institution, exacerbated by permissions set by the Financial Institution that were likely broader than intended.

**What are two of the AWS Governance practices that could have prevented such attack?**
- AWS IAM: Enforce least privileged IAM controls
- AWS S3: Ensure AWS S3 buckets do not allow public READ_ACP access, do not allow FULL_CONTROL access is limited only to specific IP addresses, have a policy to require server-side and in transit encryption for all objects stored in bucket.

Resource: 
https://www.zscaler.com/resources/white-papers/capital-one-data-breach.pdf
