*Juan Miguel Cano*

*January 09, 2024*

# Readings: Cloud Security Principles and Frameworks

**Reading 2**

[AWS Architecture Blog - Compute Abstractions on AWS: A Visual Story](https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/)

**Bookmark and Review**
- [13 Compliance Frameworks for Cloud-based Orgs](https://www.horangi.com/blog/13-compliance-frameworks-for-cloud-based-organizations)
- [Cloud Security Alliance (CSA)](https://cloudsecurityalliance.org/)
    - [Cloud Controls Matrix (CCM)](https://cloudsecurityalliance.org/research/cloud-controls-matrix/)
    - [CSA Security Guidance for Cloud Computing](https://cloudsecurityalliance.org/research/guidance/)
    
**1. Explain the levels of abstraction in AWS to someone without a technical background.**
- Lowest level (IaaS): Is like renting land and tools to build a house. You do most of the work. (AWS EC2)
- Middle level (PaaS): Is like renting a partially-built house. You complete the interior. (AWS Elastic Beanstalk)
- Highest Level (SaaS): Like renting fully furnished house. Everything's ready; just move in. (AWS Chime)
**2. What are the control plane and data plane responsible for in container abstraction?**

- Control Plane - Manages how containers, small software units, are created, organized, and scaled, like a city planner.
- Runs the containers, ensuring they have resources and are working correctly, like the land and utilities for houses.

**3. Where does AWS Lambda fall in the layers of abstraction and what makes it so special?**

- Lambda is at a very high level of abstraction. (Like a magic house that appears when you need it and vanishes when you don't) You provide the instructions (code), and it takes care of everything else-building, running, and maintaining.
- What is so Special: You don't worry about the underlying infrastructure at all. You are only charged for the exact time your code runs, making it efficient and cost-effective.

Resources: 
- https://chat.openai.com/share/89f21888-9910-4543-8e25-d53133139478
