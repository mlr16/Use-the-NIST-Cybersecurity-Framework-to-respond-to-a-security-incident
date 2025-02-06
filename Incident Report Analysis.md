# Incident Report Analysis - DDoS Attack

## Summary
| Incident Date | Incident Type | Impact |
|--------------|--------------|--------|
| incident date | DDoS Attack (ICMP Flood) | Network services down for 2 hours, affecting internal and client operations. |

**Description:**  
On day of the incident, the organization suffered a **DDoS attack** that flooded the network with **ICMP packets**, causing service downtime for **two hours**. The attack was due to **an unconfigured firewall**, which allowed unrestricted ICMP traffic. The cybersecurity team mitigated the attack by **blocking ICMP packets**, disabling non-critical services, and restoring key systems.

---

## **Identify**
| Category | Details |
|----------|---------|
| **Attack Type** | Distributed Denial of Service (DDoS) - ICMP Flood |
| **Affected Systems** | Internal network infrastructure, firewalls, routers, servers |
| **Attack Source** | Malicious actor exploiting a misconfigured firewall, possible botnet involvement |
| **Impact** | Network downtime for 2 hours, potential revenue loss, client disruptions |

---

## **Protect**
| Category | Protection Measures Implemented |
|----------|--------------------------------|
| **Firewall Configuration** | Added rules to limit ICMP packet rates |
| **Source IP Verification** | Configured firewall to block spoofed IPs |
| **Network Segmentation** | Isolated non-essential services |
| **Security Awareness Training** | Educated IT staff on firewall misconfigurations |
| **Access Control Policies** | Restricted ICMP traffic to trusted internal systems |

---

## **Detect**
| Category | Detection Tools Implemented |
|----------|----------------------------|
| **Network Monitoring** | Analyzes and detects abnormal traffic patterns |
| **IDS/IPS Deployment** | Filters and blocks ICMP flood attacks |
| **SIEM Integration** | Logs and alerts security teams about anomalies |
| **Traffic Analysis Tools** | Uses NetFlow, Wireshark, and firewall logs to identify unusual spikes |

---

## **Respond**
| Category | Response Plan |
|----------|--------------|
| **Immediate Containment** | Block ICMP packets, rate-limit traffic, take non-essential services offline |
| **Neutralization & Analysis** | Use IDS/IPS logs to trace attack source, conduct forensic traffic analysis |
| **Communication Plan** | Notify IT security teams, upper management, and stakeholders |
| **Incident Reporting** | Inform law enforcement or regulatory bodies if necessary |
| **Improvement Plan** | Conduct firewall audits, implement DDoS mitigation services |

---

## **Recover**
| Category | Recovery Actions |
|----------|-----------------|
| **Restoration Process** | Verify all network services are operational |
| **Post-Attack Analysis** | Review firewall & IDS/IPS logs to prevent future attacks |
| **Infrastructure Improvements** | Implement cloud-based DDoS protection (e.g., Cloudflare, AWS Shield) |
| **Communication Strategy** | Inform internal teams and clients about service restoration |
| **Security Policy Updates** | Enhance security policies based on incident lessons learned |

---

## **Reflections & Notes**
- **Lessons Learned:**  
   **Misconfigured firewalls can introduce serious vulnerabilities**  
   **ICMP-based attacks can be mitigated with proper firewall rules and rate-limiting**  
   **Continuous monitoring and traffic analysis are crucial for early detection**  
   **Incident response plans should be well-documented and rehearsed**  

This **incident report** follows the **NIST Cybersecurity Framework (CSF)** to ensure **proactive security measures** and improved **network resilience**.

---
