Project Goal
My objective was to conduct an investigation within the "Threat Hunting Simulator" to identify and analyze a potential security threat within the company's infrastructure. I focused on validating the hypothesis that an attacker may have leveraged a compromised third-party software package to gain initial system access and establish persistence.

Description of Actions
Throughout this project, I performed the following steps:

Context Assessment: I reviewed the briefing regarding a strange file appearing on the system and examined the Threat Intel report, which indicated a coordinated supply chain attack campaign targeting open-source ecosystems.

Documentation Review: I studied the organizational structure of PawPressMe, including employee details and their respective logged-in hosts, to better understand the environment.

Incident Analysis:

I investigated the alert queue to identify security events.

I analyzed incoming emails containing suspicious external links.

I utilized analysis tools (TryDetectThis) to verify the security of specific URLs.

Response: During the investigation, I confirmed that the firewall successfully blocked an outbound request to a blacklisted external URL.

Conclusion
As a result of my efforts, I successfully identified activity related to phishing attempts and the use of malicious links. I confirmed the effectiveness of the firewall, which blocked an attempt to connect to a malicious resource, thereby preventing the potential progression of the attack. The simulation allowed me to apply my skills in using SIEM systems, analyzing alerts, and reconstructing the attack chain.
