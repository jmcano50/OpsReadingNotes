*Juan Miguel Cano*

*February 01, 2024*

# Readings: Cloud Detective Controls


## Reading 19
[What is Amazon GuardDuty?](https://docs.aws.amazon.com/guardduty/latest/ug/what-is-guardduty.html)

## Videos

[AWS re:Inforce 2019: Threat Detection on AWS: An Introduction to Amazon GuardDuty (FND216)](https://www.youtube.com/watch?v=czsuZXQvD8E&ab_channel=AmazonWebServices)

1. What are some of the IoCs that GuardDuty can detect?
- The indicators of compromise (IOCs) that GuardDuty can detect include unusual API calls, potentially unauthorized deployments or activities, patterns indicating a possible account compromise, and communication with known malicious IP addresses.
2. What are some of the data sources which GuardDuty can use?
- GuardDuty uses VPC Flow Logs, AWS CloudTrail event logs, and DNS logs. These sources provide a comprehensive view of network activity and API calls made within your AWS environment.
3. How does GuardDuty use access behavior to spot potential malicious activity?
- They establish a baseline of normal activity for your environment. It then uses machine learning to detect deviations from this baseline, which may indicate unauthorized or malicious activity.