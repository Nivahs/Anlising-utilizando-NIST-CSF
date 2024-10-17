## Incident report analysis
**Instructions**

As you continue through this course, you may use this template to record your findings after
completing an activity or to take notes on what you've learned about a specific tool or
concept. You can also use this chart as a way to practice applying the NIST framework to
different situations you encounter.

| **Category** | **Description**                                                                                               |
|--------------|---------------------------------------------------------------------------------------------------------------|
| **Summary**  | There was an incident where the company's internal network stopped operating for 2 hours, preventing normal traffic and access to resources. The team identified a firewall misconfiguration that allowed the entry of malicious ICMP packets and took actions to block these packets.                                                        |
| **Identify** | The team audited and investigated the incident, discovering that the attack impacted the network communication due to a firewall misconfiguration, which allowed fraudulent ICMP packets from external IPs to enter. Regular audits are performed to prevent future incidents.                                                     |
| **Protect**  | The team implemented a new firewall configuration, IP verification, and network monitoring software to detect anomalies in network traffic.                                                                                                              |
| **Detect**   | Continuous monitoring was implemented with tools such as IDS and IPS to automatically detect anomalous network traffic. Proper configuration and maintenance of the firewall are essential for network security.                                                     |
| **Respond**  | The team blocked the entry of ICMP packets, preventing network overload, disabled non-critical network services, and restored critical network services.                                                                                       |
| **Recover**  | There was no data loss, only a temporary interruption of operations. The blocking of ICMP packets allowed for an immediate recovery after the incident.                                                                                              |

