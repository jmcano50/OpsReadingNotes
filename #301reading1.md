*Juan Miguel Cano*
November 26, 2023

## Layers of OSI Model

**What does “OSI” stand for?**

OSI stands for Open Systems Interconnection.
List the 7 layers of the OSI model and what each one is responsible for:

**1. Physical Layer:** The physical connection between devices. Defines the hardware elements: cables, switches, and network interface cards.

**2. Data Link Layer:** Responsible for creating a reliable link between two directly connected nodes. Includes protocols like Ethernet and PPP.

**3. Network Layer:** Manages the logical addressing and routing of data packets between different networks. IP (Internet Protocol) operates at this layer.

**4. Transport Layer:** Ensures end-to-end communication and data flow control. TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) operate at this layer.

**5. Session Layer:** Manages sessions or connections between applications. It establishes, maintains, and terminates connections.

**6. Presentation Layer:** Translates data between the application layer and the lower layers. It is responsible for data encryption, compression, and formatting.

**7. Application Layer:** Provides network services directly to end-users. It includes high-level protocols such as HTTP, FTP, and SMTP.

**Distinguish which layers are the “hardware layers” and which layers are the “software layers.” What does that even mean?**

**Hardware Layers:** Layers 1 and 2 (Physical and Data Link layers) are considered hardware layers as they deal with physical connections and the link between devices.

**Software Layers:** Layers 5 to 7 (Session, Presentation, and Application layers) are considered software layers as they are closer to the end-users and deal with software-related functionalities.

**How can the OSI model be used in troubleshooting?**
The OSI model provides a structured approach to troubleshooting network issues. Breaking down the communication process into different layers helps isolate and identify problems more efficiently. If an issue is identified in a specific layer, troubleshooting efforts can be focused on that layer without affecting the entire network.

**What Is Wireshark and How Is It Used?**

**What is Wireshark?**
Wireshark is an open-source network protocol analyzer. It allows users to capture and analyze the data traveling back and forth on a network in real-time.

**What is a packet?**
A packet is a unit of data that is transmitted over a network. It consists of the actual data being sent, along with metadata such as source and destination addresses, error-checking codes, and sequencing information.

**What 3 high-level things does Wireshark accomplish?**
**How could these be used for nefarious purposes? For benevolent purposes?**

**Capturing Packets:** Wireshark captures and displays packets, allowing users to see the content and details of each packet.

**Analyzing Packets:** It provides tools to analyze the captured packets, helping to troubleshoot network issues, identify performance bottlenecks, and detect security threats.

**Filtering Packets:** Wireshark allows users to apply filters to focus on specific types of packets, making it easier to pinpoint relevant information.
For Nefarious Purposes: In the wrong hands, Wireshark could be used to capture sensitive information, such as login credentials or personal data, as it can intercept unencrypted traffic.

**For Benevolent Purposes:** It is an essential tool for network administrators and security professionals to monitor and secure network traffic, identify and address performance issues, and ensure the overall health of a network.
 

**Resources Used:**
https://www.geeksforgeeks.org/layers-of-osi-model/Links

https://www.comptia.org/content/articles/what-is-wireshark-and-how-to-use-itLinks 

https://www.professormesser.com/network-plus/n10-008/n10-008-video/understanding-the-osi-model-3/Links 

https://www.professormesser.com/network-plus/n10-008/n10-008-video/data-communication/Links 

https://www.youtube.com/watch?v=aD_yi5VjF78Links 
