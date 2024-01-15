*Juan Miguel Cano*

*January 15, 2024*

# Readings: Data file encryption

## Reading 6 

[Applying The CIA Triad To Your Enterprise File Transfer](https://www.jscape.com/blog/implementing-the-cia-triad-when-transferring-files-through-the-internet)

[What Are MD5, SHA-1, and SHA-256 Hashes, and How Do I Check Them?](https://www.howtogeek.com/67241/htg-explains-what-are-md5-sha-1-hashes-and-how-do-i-check-them/)

1. You have been made responsible for the company’s file server. How would you preserve the three elements of the CIA triad?
- Confidentiality: Ensure that data is accessible only to those who are authorized.
    - Implement strong access control measures.
        - Password protection
        - User authentication
        - Encryption of sensitive files

- Integrity: Maintain the accuracy and consistency of data over its entire lifecycle.
    - Implement regular backups using the following to verify data integrity:
        - Checksums
        - Hashing algorithms
        - Set up intrusion detection systems to alert of any unauthorized changes to the data.
- Availability: Ensure that data and resources are available to authorized users when needed.
    - Implement the following for data availability:
        - Maintaining the hardware and network infrastructure using:
            - Redundancy
            - Failover techniques:
                - RAID (Storage and load balancing for network traffic)
            - Robust disaster recovery plan ( to mitigate the impact of hardware failure, natural disasters, or cyber-attacks.)


2. Explain how hashing verifies data integrity using non-technical terms.
- Think of a bottle of whisky as data or a file you want to protect. Each bottle of whisky has a unique flavor profile, this flavor profile is like the hash value in the digital world.

     When a whisky is made, its flavor profile is recorded. To check if the whisky is genuine and unchanged, you compare its current flavor with the recorded profile. If they match, the whisky is authentic and unaltered. 
     
     Similarly, hashing a file creates a unique value (hash). To check if the file has been tampered with, you recompute the hash and compare it with the original. If they match, the file is unchanged. Just like a small change in whisky ingredients alters its flavor, a tiny change in data results in a different hash, indicating alteration.

3. How are hashing and encryption different?
- Hashing: Is a one-way process, like a fruit smoothy. Once you blend the fruit, you cannot turn the smoothy back to whole fruit. 
    - Hashes are used to the verify data integrity and authenticity, not for concealing data.

- Encryption: This is a two-way process, like using a passcode to lock your cell phone. You encrypt data to make it unreadable to anyone who doesn't have the passcode, and you can decrypt it to return it to its original form, like giving someone your password to open your phone. 
    - Encryption is used for maintaining confidentiality, ensuring that only authorized parties can access and read the data.
