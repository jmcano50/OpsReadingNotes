*Juan Miguel Cano*

*January 18, 2024*

# Readings: Public Key Infrastructure (PKI)

## Reading 9
[What is Public Key Infrastructure (PKI)](https://www.ssh.com/pki/)

## Name the three main components that make up PKI.

**How would you explain, to a non-technical friend, the role PKI plays in protecting traffic between your browser and a web server?**
    
-   Certificate Authority: A trusted entity that issues digital certificates.
- Registration Authority:  Is responsible for accepting requests for digital certificates and authenticating the early making of the request before passing the request to the CA. RA is often considered as part of the CA, but it can also be a separate entity.
- Digital Certificates: These are electronic documents that use a digital signature to bind a public key with an identity; information such as the name of a person or an organization, their address, and so forth. Digital certificates can be used to encrypt data and digitally sign documents, emails, and transactions to ensure the security and integrity of the data.

What is the main weakness of the PKI architecture?
PKI's weakness lies in its complexity and dependency on trust. Managing a large number of certificates and keys is intricate and challenging, making the system vulnerable if not done correctly. PKI relies heavily on Certificate Authorities (CAs) for issuing and managing certificates, meaning any compromise of these authorities can undermine the entire system. Problems also arise with certificate revocation, which can be inefficient, posing additional security risks. Additionally, the cost and resources required for implementing and maintaining PKI can be prohibitive, especially for smaller organizations. Finally, the system's effectiveness can be compromised by user errors, such as mishandling private keys or misunderstanding security prompts.

## Videos
[Prof Messer Security+ PKI Components](https://www.youtube.com/watch?v=3yuad7_bszE)