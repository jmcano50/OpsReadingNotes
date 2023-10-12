Juan Miguel Cano								October 12, 2023

# Class 7

## Readings: Network Connectivity

Below, you will find some reading materials and videos that support today’s topic and the upcoming lecture.
Reading

**SSH Protocol**

**1.	What is the Secure Shell (SSH) Protocol?**

The SSH Protocol is a secure remote login and file transfer method offering strong authentication, encryption, and data integrity. It is used for secure access, file transfers, and remote command execution.

**2.	What are the typical uses of the SSH protocol?** 

•	Providing secure access for users and automated processes.
•	Interactive and automated file transfers.
•	Issuing remote commands.
•	Managing network infrastructure and critical system components.

**3.	How does the SSH protocol work?**	

The SSH protocol works in a client-server model. The client initiates a connection using public key cryptography to verify the server's identity. Symmetric solid encryption and hashing algorithms secure data exchange between the client and server, ensuring privacy and integrity.

**4.	How is the data kept safe when transmitted between the SSH client and server?**

•	Data is kept safe during transmission in SSH through:

1.	Strong Encryption: SSH uses symmetric solid encryption algorithms like AES.
2.	Data Integrity: Standard hash algorithms like SHA-2 ensure data is not tampered with.
3.	Secure Key Exchange: Public key cryptography verifies the server's identity and securely exchanges keys.
4.	Encrypted Channel: All data transferred over the connection is encrypted, preventing eavesdropping.

**5.	What is SFTP?**	

SFTP stands for "SSH File Transfer Protocol." It is a secure file transfer protocol that runs over SSH. SFTP provides a secure way to transfer files between computers, ensuring data encryption and integrity. It is a safer alternative to traditional FTP for secure file transfers.

**What is RDP? And how to use it?**

•	RDP (Remote Desktop Protocol) is a Microsoft-developed protocol for remote computer access. To use it:
o	Enable RDP on the host computer.
o	Find the host computer's IP address or hostname.
o	Use an RDP client on your computer to connect.
o	Enter host details and connect.
o	Interact with the host computer remotely.

**1.	What is Windows Remote Desktop Connection?**

Windows Remote Desktop Connection is a built-in feature in Microsoft Windows that allows users to connect to a remote Windows-based computer over a network connection. It enables remote access and control of a remote computer as if you were physically in front of it. This feature is commonly used for remote administration, technical support, or accessing your computer from a different location.

**2.	What is RDP?**

RDP (Remote Desktop Protocol) is a Microsoft-developed protocol for remote computer access

**3.	What is the RDP port number?**	

The default port number for RDP (Remote Desktop Protocol) is 3389. This port is used for RDP connections on Windows-based computers. However, it is essential to note that changing the default RDP port to a non-standard port is often recommended for security reasons to help protect against unauthorized access and security threats.
