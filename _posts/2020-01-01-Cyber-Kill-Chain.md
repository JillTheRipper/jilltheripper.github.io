---
layout: post
title: Cyber Kill Chain
categories: [Try Hack Me, Cyber Defence Framework]
tags: [try hack me]     # TAG names should always be lowercase
---

## Task 1 : Introduction

No Q&A

## Task 2 : Reconnaissance

### Q&A:

What is the name of the Intel Gathering Tool that is a web-based interface to the common tools and resources for open-source intelligence? `OSINT Framework`

What is the definition for the email gathering process during the stage of reconnaissance? `email harvesting`

## Task 3 : Weaponization

### Q&A:

This term is referred to as a group of commands that perform a specific task. You can think of them as subroutines or functions that contain the code that most users use to automate routine tasks. But malicious actors tend to use them for malicious purposes and include them in Microsoft Office documents. Can you provide the term for it? `Macro`

## Task 4 : Delivery

### Q&A:

What is the name of the attack when it is performed against a specific group of people, and the attacker seeks to infect the website that the mentioned group of people is constantly visiting. `Watering hole attack`

## Task 5 : Exploitation

### Q&A:

Can you provide the name for a cyberattack targeting a software vulnerability that is unknown to the antivirus or software vendors? `Zero-Day`

## Task 6 : Installation

### Q&A:
Can you provide the technique used to modify file time attributes to hide new or changes to existing files? `Timestomping`

Can you name the malicious script planted by an attacker on the webserver to maintain access to the compromised system and enables the webserver to be accessed remotely? `web shell`

## Task 7 : Command and Control

### Q&A:

What is the C2 communication where the victim makes regular DNS requests to a DNS server and domain which belong to an attacker. `DNS tunneling`

## Task 8 : Actions of objectives (Exfiltration)

### Q&A:

Can you provide a technology included in Microsoft Windows that can create backup copies or snapshots of files or volumes on the computer, even when they are in use? `shadow copy`

## Task 9 : Practice Analysis

### Q&A:

![](/assets/images/ckc10.jpg)

What is the flag after you complete the static site? `THM{7HR347_1N73L_12_4w35om3}`


## Task 10 : Conclusion

Cyber Kill Chain can be a great tool to improve network defence. Is it perfect and can it be the only tool to rely on? No. 

The traditional Cyber Kill Chain or Lockheed Martin Cyber Kill Chain was last modified in 2011, which, if you remember, is the date of its establishment. The absence of updates and modifications creates security gaps. 

The traditional Cyber Kill Chain was designed to secure the network perimeter and protect against malware threats. But the cybersecurity threats have developed drastically nowadays, and adversaries are combining multiple TTP (tactics, techniques, and procedures) to achieve their goal. Adversaries are capable of defeating threat intelligence by modifying the file hashes and IP addresses. Security solutions companies are developing technologies like AI (Artificial Intelligence) and different algorithms to detect even slight and suspicious changes. 

Since the main focus of the framework is on malware delivery and network security, the traditional Cyber Kill Chain will not be able to identify **Insider Threats**. According to [CISA](https://www.cisa.gov/defining-insider-threats), _"The Insider Threat is the potential for an insider to use their authorized access or understanding of an organization to harm that organization."_

We recommend not only relying on the traditional Cyber Kill Chain model but also referring to [MITRE ATT&CK](https://attack.mitre.org/) as well as [Unified Kill Chain](https://unifiedkillchain.com/) to apply a more comprehensive approach to your defence methodologies.
