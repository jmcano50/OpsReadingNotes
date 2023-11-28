*Juan Miguel Cano*

November 27, 2023

## Network scanning with NMAP
**Reading 2**

For Lecture & Lab

**What is a Port Scanner and How Does it Work?**

- A port scanner is a computer program that checks network ports for one of three possible statuses - open, closed, or filtered.

**What is a port? Describe it with an analogy that would help a family member understand.**

-  A port is a virtual location where networking communication starts and ends.

- Your (computer) would be a Latin dance studio that teaches Salsa, Bachata, Merengue, Rumba, and ChaChaCha;
- the Classes and Staff would be the (different ports) with a specific focus on each dance. 
- Your (Web browsing port) is the street window looking into the studio at the different Latin Dances. 
- The basic class Taste of Salsa is the (file-sharing port) where couples learn to synchronize the correct moves for the Latin Dances. 
- The Dance Instructors are the (email port) where they communicate to you how to synchronize the different types of moves. 
- Each of the different dance classes is a (port) to specialize in the individual Latin Dances. 
- When there is a need to advance to a higher level (data transfer), it is assigned to specific a specific audition (Port) to ensure the dancer will graduate to the next level. 
- The Dance Studio’s Administration Staff responsible for the building, instructors, classes, auditions, and scheduling is the (computer’s operating system) they overseas everything building, instructors, and classes (all the ports), ensuring the right instructors (data) and assigned to the correct Salsa, Bachata, Merengue, Rumba and ChaChaCha classes specializing in the specific dance (ports)

**What does a port scanner send to a port to check the current status?**

- A port scanner sends a packet of network data to a port to check the current status.

**When a port scanner sends a request to connect, what are the three possible responses? Describe them.**
- Open, Accepted: The computer responds and asks if there is anything it can do for you.
- Closed, Not Listening: The computer responds that “This port is currently in use and unavailable at this time.”
- Filtered, Dropped, Blocked: The computer doesn’t even bother to respond.

**What is the difference between TCP and UDP?**
- TCP (Transmission Control Protocol) is an orderly transaction protocol: TCP sends each packet in order, complete with error checking, verification, and a 3-way handshake to confirm each packet is successful.
- UDP does not have any error checking but tends to be faster. Live streaming and online video games often use UDP for this reason. UDP is a connectionless protocol, so programs that use UDP just send the data - and if you miss a packet, you will never get it again.

**Common Ports**

**List and describe the ports used for the following:**
- **Telnet** - TCP port 23: used for remote terminal access.
- **SSH** - TCP port 22: used for secure remote access to a device over a network
- **DNS** - UDP port 53: used to translate human-readable domain names into IP addresses.
- **SMTP** - TCP port 25: used for the transmission of email between servers.
- HTTP** - TCP port 80: is the foundation of data communication on the World Wide Web.
- **HTTPS** - TCP port 443: is the secure version of HTTP. It uses encryption (SSL/TLS), commonly used for secure transitions on the web, to ensure secure data transfer.
- **RDP** - TCP port 3389: is a proprietary protocol developed by Microsoft. It provides a user with a graphical interface to connect to another computer over a network connection.
- **Ping** - ICMP: doesn’t use a specific port but relies on Internet Control Message Protocol (ICMP). It is a network diagnostic tool used to test the reachability of a host on an Internet Protocol (IP) network.

**Resources Used:**
 
https://chat.openai.com/share/205e9823-a466-4649-8a1f-28ec6de82c9c

https://www.varonis.com/blog/port-scanning-techniques/

https://www.professormesser.com/network-plus/n10-008/n10-008-video/common-ports-n10-008/

https://chat.openai.com/share/bd2f73f5-f3a4-44d3-b9d8-d23ca6980653
