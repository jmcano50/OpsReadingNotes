*Juan Miguel Cano*

*February 13, 2024*

# Readings: Persistence

## Reading 27
[PowerShell Empire No Longer Maintained](https://www.bleepingcomputer.com/news/security/powershell-empire-framework-is-no-longer-maintained/)

- While no longer maintained by its original creator as of writing, PowerShell Empire has been forked many times and was used by nation-state actors from 2015-2019. The PowerShell Empire project is now actively maintained by BC Security. As you read this article, take note of its original purpose as well as the tactical advantages offered to its users.
1. What is one of the major advantages of PowerShell Empire?
- One major advantage of PowerShell Empire is its ability to evade traditional antivirus and endpoint detection systems. This is due to its use of PowerShell scripting language, which is often trusted and allowed to execute on systems, making it harder for security measures to detect malicious activities.
2. What are some of the APT groups that have been known to use PS Empire and into which step of the Cyber Kill Chain does the use of PS Empire fall?
- Several advanced persistent threat (ATP) groups have been known to use PowerShell Empire, including APT29 (also known as Cozy Bear), APT32 (also known as OceanLotus), and APT33 (also known as Elfin). The use of PowerShell Empire typically falls into the "exploitation" step of the Cyber Kill Chain, where attackers gain access to the target system.
3. What are the four main components needed to pull off an attack using PS Empire?
- **Listener:** This is the component that listens for incoming connections from compromised systems.
- **Module:** PowerShell Empire provides a wide range of modules that attackers can use to perform various actions on compromised systems, such as gathering information, executing commands, or exfiltrating data.
- **Agent:** Once a system is compromised, an agent is implanted in it, allowing the attacker to maintain persistent access and control.
- **Stager:** This is a piece of code used to initially compromise a system and deploy the agent. It can be delivered through various means, such as phishing emails or exploit kits.
## Bookmark and Review
- [Hacking with Empire – PowerShell Post-Exploitation Agent](https://www.hackingarticles.in/hacking-with-empire-powershell-post-exploitation-agent/)

## Resources:
- https://www.bleepingcomputer.com/news/security/powershell-empire-framework-is-no-longer-maintained/
- https://chat.openai.com/share/ee90d239-c80b-4081-b4d4-a639669cf34e
- https://www.hackingarticles.in/hacking-with-empire-powershell-post-exploitation-agent/
