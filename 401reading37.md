*Juan Miguel Cano*

*February 27, 2024*

# Readings: Automated AppSec with ZAP

## Reading 37
[Getting Started with Zed Attack Proxy](https://www.zaproxy.org/getting-started/)

1. What are the three common stages of the Penetration Testing process, and what tasks are performed at each one?
    - Planning and Reconnaissance: Define the test's scope and goals, and gather information on the target.
    - Scanning: Use tools to understand the target's response to intrusion attempts and identify vulnerabilities.
    - Gaining Access and Exploitation: Attempt to exploit vulnerabilities to see what unauthorized data can be accessed.
2. Explain a “main-in-the-middle proxy” in non-technical terms.
    - Imagine you're a Marine officer issuing orders to your platoon. You send these orders down the chain of command, not directly to the individual Marines but through your subordinate leaders. Your platoon Sergeant, then to your squad leaders, and finally to the individual Marines. This structured path of communication acts as a "Man-in-the-Middle Proxy."
    - At each step, the person in the chain has the authority to interpret your orders and add context or additional instructions based on their understanding and the situation on the ground before passing it down. This ensures that the orders are executed in a manner that aligns with the immediate conditions and overarching mission objectives, much like a Man-in -the-Middle Proxy inspects and potentially modifies information to ensure it aligns with certain criteria or security policies or possibly in their own vested interest. 
3. What are the 2 spiders available for use in ZAP?
    - Traditional Spider: Best for static pages. It follows links to map the site's structure.
    - AJAX Spider: Suited for dynamic, JavaScript-heavy pages. It interacts with elements to map the site.
4. What situations are they best suited for?
    - Traditional Spider: Good for simple, less dynamic websites where content doesn't change much without user actions.
    - AJAX Spider: Best for complex, modern web applications where content updates dynamically and is heavily dependent on user interactions.

## Bookmark and Review
- [Python Tools for Cyber](https://hackersonlineclub.com/python-tools/)