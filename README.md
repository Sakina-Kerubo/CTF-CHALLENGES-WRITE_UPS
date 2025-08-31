_______________________________________
🎥 Webcam Phishing Simulation Using CamPhish (Cloudflare Tunnel)
🧠 Objective
To ethically simulate a webcam phishing attack using CamPhish, a social engineering tool that exploits browser-based camera permissions. This lab was conducted in a controlled environment to demonstrate how attackers might gain unauthorized access and to reinforce defensive awareness.
________________________________________
🛠️ Tool Used
CamPhish — A phishing toolkit that creates fake web pages requesting webcam access. Once permission is granted, it captures snapshots from the target’s webcam. It uses:
•	PHP for page rendering
•	Cloudflare Tunnel for secure public URL exposure
•	Browser permission prompts to initiate camera access
________________________________________
⚙️ Setup & Execution
1. Environment Preparation
•	OS: Kali Linux
•	Dependencies: Git, PHP, Cloudflare Tunnel
git clone https://github.com/techchipnet/CamPhish.git  
cd CamPhish  
bash camphish.sh  
<img width="345" height="249" alt="image" src="https://github.com/user-attachments/assets/46b104b3-5868-4388-a497-539afe3489e8" />

CamPhish initialized with Cloudflare tunneling option.
________________________________________
2. Phishing Link Generation
•	Selected Cloudflare Tunnel for stable public URL exposure
•	CamPhish generated a phishing link mimicking a verification or login page
 <img width="496" height="213" alt="image" src="https://github.com/user-attachments/assets/94bf926d-0bb1-41b4-b5cc-bba5e4f5d332" />

Phishing link generated via Cloudflare Tunnel for webcam access simulation.
________________________________________
3. Simulated Victim Interaction
•	Shared the link with a consented lab subject
•	Subject clicked the link and granted webcam access
•	CamPhish captured snapshots and stored them locally
 <img width="158" height="240" alt="image" src="https://github.com/user-attachments/assets/42d3623b-6c60-4d79-9fa8-b5a7ca027cf0" />
 
 Simulated phishing page requesting webcam access.
 
 <img width="446" height="291" alt="image" src="https://github.com/user-attachments/assets/26ee3ad1-7f03-4ab4-a35a-3619024580b9" />

Snapshots stored in CamPhish output folder.
________________________________________
🔍 Observations
•	The phishing page was visually convincing
•	Browser permission prompts were present but easily overlooked
•	Snapshots were only captured after explicit permission—highlighting user awareness as a key defense
________________________________________
🛡️ Ethical Boundaries
This demonstration was conducted in a controlled lab environment with full consent. No real-world exploitation occurred. The purpose was to:
•	Understand attacker tactics
•	Educate users on phishing risks
•	Reinforce ethical hacking principles
________________________________________
🧩 Mitigation Strategies
•	Inspect URLs before clicking
•	Deny unnecessary camera/microphone permissions
•	Use browser extensions like uBlock Origin or NoScript
•	Educate users on social engineering tactics
________________________________________
📘 Reflection
This exercise sharpened my understanding of phishing mechanics and the psychology behind permission-based attacks. It also reinforced the importance of ethical hacking in exposing vulnerabilities before they’re exploited maliciously.
________________________________________
