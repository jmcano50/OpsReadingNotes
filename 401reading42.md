*Juan Miguel Cano*

*March 05, 2024*

# Readings: Pass the Hash with Mimikatz

## Reading 42
[What is Mimikatz?](https://www.varonis.com/blog/what-is-mimikatz/)

1. Name the six credential-gathering techniques which Mimikatz is able to perform and explain how two of them work.
    - LSASS Dumping: Mimikatz can extract passwords, hashes, and Kerberos tickets from the LSASS (Local Security Authority Subsystem Service) process memory.
    - Pass-the-Hash (PtH): It uses hash values of user passwords to authenticate as that user without needing the actual plaintext password.
    - Pass-the-Ticket (PtT)
    - Over-Pass-the-Hash(Over-PtH)
    - Kerberos Golden Ticket
    - Kerberos Silver Ticket
2. What are four ways we can defend against Mimikatz attacks? Explain how two of the mitigations can stop Mimikatz.
    - Using Local Administrator Password Solution (LAPS)
    - Implementing Credential Guard in Windows
    - Restricting Administrative Privileges
    - Enabling Multi-Factor Authentication (MFA)

Explanation of Mitigations:

1. Using LAPS: By frequently changing and uniquely setting local administrator passwords across computers, LAPS makes it difficult for attackers to move laterally using stolen credentials, as each machine requires a different password.

2. Implementing Credential Guard: It leverages hardware and virtualization-based security to protect credential derivatives, preventing Mimikatz from accessing and using them, thus thwarting many of its credential theft capabilities.