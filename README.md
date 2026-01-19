# Security Risk Assessment Report

## Overview
This repository contains a security risk assessment report focusing on
network and system hardening techniques to protect organizational and
customer data from cyber threats.

## Scope
The report covers:
- Intrusion Detection Systems (IDS)
- Intrusion Prevention Systems (IPS)
- Next-Generation Firewalls (NGFW)
- Multi-Factor Authentication (MFA)
- Strong password policies
- Zero Trust security model

## Purpose
The goal of this assessment is to identify effective security controls
and explain how they reduce risk, improve data confidentiality, and
minimize the attack surface.

## Author
SERION
# Security Risk Assessment Report

## Part 1: Hardening Tools and Methods

### Intrusion Prevention System (IPS)
An Intrusion Prevention System helps detect and block malicious activity
on the network or system in real time. By actively preventing attacks,
IPS reduces the attack surface and protects sensitive customer and
organizational data from malicious threat actors.

### Intrusion Detection System (IDS)
An Intrusion Detection System monitors network and system activity to
identify anomalies and potential security threats. IDS alerts
administrators before a breach escalates, allowing timely investigation
and mitigation to protect company and customer data.

### Next-Generation Firewall (NGFW)
Next-generation firewalls act as a proactive boundary defense by
filtering incoming and outgoing traffic based on predefined security
rules. NGFWs also perform deep packet inspection, allowing only required
ports and services while blocking unwanted communication, reducing the
risk of network-based attacks.

---

## Part 2: Security Recommendations

### Multi-Factor Authentication (MFA)
Multi-Factor Authentication should be implemented across the
organization for both user and administrator accounts. MFA enhances
confidentiality and privacy by requiring multiple forms of verification,
including something the user knows (password), something they have
(phone or security token), and something they are (biometrics such as
fingerprints). This significantly reduces unauthorized access risks even
if credentials are compromised.

### Strong Password Policies and Zero Trust
The organization should enforce strong password policies and prohibit
password sharing. Default administrative passwords must be changed
immediately, as they are a common attack vector. Passwords should be at
least 12 characters long and include letters, numbers, and special
characters. Centralized password management combined with a Zero Trust
security model ensures that no user or device is trusted by default,
strengthening access control.

### Firewall Rule Management
Firewalls should be configured with strict and regularly updated rules.
Only necessary ports and services should be allowed, while unnecessary
traffic is blocked. This minimizes unwanted communication, reduces the
attack surface, and helps prevent unauthorized access and network-based
attacks.

---

## Conclusion
Implementing layered security controls such as IDS, IPS, next-generation
firewalls, MFA, and strong access control policies provides defense in
depth. These measures significantly improve the confidentiality,
integrity, and availability of organizational and customer data.

