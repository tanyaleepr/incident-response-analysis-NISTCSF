# Incident Response Analysis using NIST CSF framework (Identity, Protect, Detect, Respond, and Recover)

![license badge](https://img.shields.io/badge/license-MIT-brightblue)
    
## Description
A multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, the organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

The assignment was tasked with using this security event to create a plan to improve the company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). I used the CSF to help navigate through the different steps of analyzing this cybersecurity incident and integrate my analysis into a general security strategy:




* Identity:
  * Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security. 

* Protect:
  * Internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats. 

* Detect:
  * Detecting potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections. 

* Respond:
  * To contain, neutralize, and analyze security incidents; implement improvements to the security process. 

* Recover:
  * Affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.

![framework-01](https://github.com/tanyaleepr/incident-response-analysis-NISTCSF/assets/92898110/f7690c8d-66e7-4f7d-912d-06eab078f6a4)




