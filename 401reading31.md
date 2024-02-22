*Juan Miguel Cano*

*February 19, 2024*

# Readings: Malware Detection with YARA Rules

## Reading 31
[What Are YARA Rules?](https://archerint.com/what-are-yara-rules/)

[Threat Hunting using YARA](https://www.geeksforgeeks.org/threat-hunting-using-yara/)

1. What is the main goal of Threat Hunting, and how is it different from traditional threat monitoring?
- Threat hunting aims to proactively identify threats within a network, unlike traditional monitoring, which is more reactive. It involves actively searching for signs of malicious activity or anomalies.
2. What are the four types of YARA rules, and what does each one of them use to identify and classify malicious software?
- The four types of YARA rules are: String rules (use specific strings or sequences of bytes), Binary rules (analyze binary structure), Condition rules (define conditions for a file to be considered malicious), and Meta rules (provide metadata about the file).
3. How are YARA rules similar to how Anti-Virus programs detect malicious software?
- YARA rules, like Anti-Virus programs, detect malicious software by analyzing files for specific signatures or patterns associated with known malware. However, YARA rules offer more customization and flexibility for security analysts.

## Bookmark and Review
- [YARA Rules GitHub Project](https://github.com/Yara-Rules/rules)
    - This project covers the need of a group of IT Security Researchers to have a single repository where different Yara signatures are compiled, classified, and kept as up-to-date as possible, and began as an open source community for collecting Yara rules.