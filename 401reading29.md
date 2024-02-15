*Juan Miguel Cano*

*February 15, 2024*

# Readings: Modeling a Web Application

## Reading 29
[Application Threat Modeling](https://owasp.org/www-community/Application_Threat_Modeling)

[A Beginners Guide To The STRIDE Security Threat Model](https://www.ockam.io/learn/blog/introduction_to_STRIDE_security_model)

1. **Explain threat modeling using real-world non-technical examples.**
- Think of a building  a house in a neighborhood known for occasional break-ins. Before starting construction, you would want to assess potential security threats to your house and take steps to mitigate them. This could involve installing sturdy locks on doors and windows, adding security cameras, and ensuring proper lighting around the property. Additionally, you might consider factors like the location of the house, nearby escape routes, and the likelihood of burglary based on past incidents in the area.

- In this analogy:
    - Your house represents the web application.
    - Security threats such as break-ins represent potential risks to the application.
    - Measures like locks, cameras, and lighting represent security controls or countermeasures.
    - Factors like location and past incidents represent the context and environment in which the application operates.

2. **What are the four questions that can help us organize threat modeling?**
- 1. **What are we building?** This question helps identify the scope of the system or application being developed. It involves understanding its functionalities, components, data flows, and dependencies.
- 2. **What can go wrong?** Here, the focus is on identifying potential threats and vulnerabilities that could compromise the security of the system. This could include unauthorized access, data breaches, denial-of-service attacks, and more.
- 3. **What are we going to do about it?** Once threats and vulnerabilities are identified, this question addresses how the team plans to mitigate or eliminate them. It involves selecting and implementing appropriate security controls, best practices, and countermeasures.
- 4. **Did we do a good enough job?** After implementing security measures, it's essential to evaluate their effectiveness and reassess the threat landscape periodically. This ongoing process helps ensure that security measures remain robust and up-to-date.

3. **You are the project lead for a new application. How would you explain the benefits of Threat Modeling to the rest of the team?**
- **Enhanced Security:** Threat modeling enables us to proactively identify and address security risks, reducing the likelihood of security breaches, data leaks, and other cyber threats.
- **Cost Savings:** By identifying security issues early in the development process, we can avoid costly fixes and minimize the potential impact of security incidents on the application and the organization.
- **Compliance:** Many industries and regulatory frameworks require organizations to implement adequate security measures to protect sensitive data. Threat modeling helps ensure compliance with these requirements.
- **Improved Collaborations:** Engaging the team in threat modeling encourages collaboration and shared responsibility for security; It allows developers, architects, and stakeholders to contribute their insights and expertise to enhance the application's security posture.
- **Risk Prioritization:** Threat modeling helps prioritize security efforts by focusing on the most critical threats and vulnerabilities that pose the highest risk to the application and its users.
- **Continuous Improvement:** Threat modeling is not a one-time activity but an iterative process. It promotes continuous improvement by regularly assessing and updating security measures to adapt to evolving threats and changes in the application's environment.

## Bookmark and Review
[Threat Modeling Security Fundamentals](https://docs.microsoft.com/en-us/learn/paths/tm-threat-modeling-fundamentals/)

## Resources:
- https://owasp.org/www-community/Application_Threat_Modeling
- https://www.ockam.io/learn/blog/introduction_to_STRIDE_security_model
- https://chat.openai.com/share/13000ee3-0416-4fbd-a590-1710aef46179
- https://docs.microsoft.com/en-us/learn/paths/tm-threat-modeling-fundamentals/