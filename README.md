# DF_case_study
- Digital Forensic Case study using **magnet axiom** , **volatility** , **autopsy**
- Case Study Report is in the document

# SCENARIO OVERVIEW
‘John Doe’ was a long-serving employee working in the IT operations department of a reputed company named TechNova Pvt. Ltd., which maintained sensitive internal tools and proprietary systems. Disgruntled over a denied promotion and unsatisfactory appraisal, John began searching for methods to disrupt the company’s infrastructure.
Initially, John tried to find network-based viruses and cyberattack techniques through web searches but failed to find anything actionable. He then came across online forums (like Reddit) discussing how to hire hackers via the Tor network. Intrigued, John downloaded and installed the Tor browser on his personal laptop and began exploring .onion forums.
Through a darknet marketplace, John contacted a hacker alias "Anonymous01", who offered him a fileless malware variant known as “99_BlackEnergy” capable of crashing internal networks. After negotiating payment and receiving instructions via email (Outlook), the hacker sent him the malware file disguised as a .bat loader.
John downloaded the virus to a USB drive, along with a set of anti-forensic tools (e.g., Winlogbeat tampering scripts) to cover his tracks. He also installed VeraCrypt to create an encrypted hidden volume on the USB to hide communication logs, screenshots, and plans shared by the hacker, including a PDF flowchart of the attack sequence.
John later accessed the TechNova office during off-hours and plugged the USB into a company PC. He installed the malware and anti-forensic tools, executed the virus, and allowed it to spread across the company’s internal network. The malware began replicating and caused noticeable slowdowns and system crashes.
TechNova’s internal monitoring systems flagged unusual memory usage, prompting a security investigation. John was stopped during a routine security checkpoint while leaving the premises. His personal laptop and USB drive were seized. A RAM dump of the infected company PC was taken for forensic investigation.
The following devices were sent to the digital forensics lab for examination:

●	John Doe’s personal laptop (HDD imaging and search history inspection)
●	Malicious USB device (partition suspected)
●	Memory image of the infected company PC (to analyze malware activity using Volatility)
