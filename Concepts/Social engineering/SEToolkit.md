# Social Engineering Attack Simulation Using SET

> ⚠️ **Disclaimer:** This project was performed only in a controlled lab environment for cybersecurity education and authorized testing. No real users, credentials, or third-party systems were targeted. The purpose of this project is to understand how social engineering attacks work so that organizations and users can better defend against them.

## 📌 Project Overview

As part of my hands-on cybersecurity learning journey, I practiced a controlled social engineering attack simulation using the **Social-Engineer Toolkit (SET)**.

The objective of this lab was to understand the complete attack flow from the attacker's perspective in a safe environment.

The practical exercise included:

- Using the Social-Engineer Toolkit (SET)
- Exploring Website Attack Vectors
- Cloning a webpage in a controlled lab
- Creating a demonstration payload
- Configuring a listener in a lab environment
- Hosting controlled files using a local HTTP server
- Observing how submitted data can be captured
- Verifying a successful session inside the isolated lab
- Understanding the security risks associated with social engineering

This project helped me understand an important cybersecurity lesson:

> Technical security alone is not enough. Human interaction is often one of the biggest attack surfaces.

---

## 🎯 Learning Objectives

The main objectives of this lab were:

1. Understand the basics of social engineering.
2. Learn how the Social-Engineer Toolkit works.
3. Explore webpage cloning in a controlled environment.
4. Understand how fake login pages can be used to capture submitted information.
5. Learn the concept of payload creation and listener configuration.
6. Understand the importance of network configuration.
7. Observe how a simulated compromised session appears in a controlled environment.
8. Learn how organizations can defend against these techniques.



# 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Attack simulation environment |
| Social-Engineer Toolkit (SET) | Social engineering simulation |
| Metasploit Framework | Controlled listener and session management |
| Python HTTP Server | Local file hosting |
| Web Browser | Accessing the cloned webpage |
| DVWA | Deliberately vulnerable web application used in the lab |



# 🧪 Lab Environment

This project was performed in an isolated and authorized environment.

The environment contained:

- An attacker/testing machine running Kali Linux
- A deliberately vulnerable web application
- A controlled victim/test machine
- Private laboratory network addresses
- No real users or production systems

Using an isolated environment is important because social engineering and credential-harvesting techniques can cause serious harm if performed without authorization.



# 🔄 Attack Simulation Workflow

The overall workflow followed in this lab was:

```text
SET
 │
 ▼
Social Engineering Attacks
 │
 ▼
Website Attack Vectors
 │
 ▼
Credential Harvester / Site Cloning
 │
 ▼
Controlled Webpage Clone
 │
 ▼
Test User Interaction
 │
 ▼
Submitted Data Captured in Lab
 │
 ▼
Payload Demonstration
 │
 ▼
Listener Configuration
 │
 ▼
Controlled Session Verification



