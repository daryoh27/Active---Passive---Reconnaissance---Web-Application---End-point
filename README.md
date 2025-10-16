# Active---Passive---Reconnaissance---Web-Application---End-point
## Overview
Reconnaissance is the information-gathering phase of security assessments. It reveals what an attacker—or a defender—can learn about a target before any intrusion attempts. Reconnaissance generally falls into two categories: active and passive. This post explains the difference, common methods (at a conceptual level), legitimate use cases.

## Definitions
## Passive Reconnaissance
Gathering information about a target without direct interaction that would be visible to the target’s systems. Examples include searching public records, browsing DNS/WHOIS data, OSINT (public social media/profile mining), and monitoring public-facing resources. Passive techniques minimize the chance of detection.

## Active Reconnaissance
Gathering information by interacting directly with the target’s systems or network in ways that may be logged or noticed. This can include probing services, scanning open ports, or requesting resources. Active recon yields more precise technical details but carries a higher risk of detection and, if done without permission, legal ramifications.

## Conceptual Methods (Non-actionable)

## Passive methods (conceptual)

- Open-source intelligence (OSINT): public web pages, social media, job postings that reveal software stacks or network structure.

- Public DNS/WHOIS records and certificate transparency logs.

- Public repositories and documentation that reveal infrastructure or credentials by mistake.

## Active methods (conceptual)

- Service and port enumeration: interacting with network hosts to determine listening services and versions.

- Banner grabbing and protocol probing to identify software and versions.

- Active DNS queries or direct API calls that reveal configuration details.

## Note: This document deliberately does not include commands, tool configurations, or step-by-step instructions for active scanning. Active reconnaissance can be abused; always operate within legal boundaries and with explicit authorization.

## Ethical & Legal Considerations
- Get written authorization before performing any active reconnaissance on systems you do not own.

- Passive gathering from public sources is generally legal, but respect privacy and terms of service.

- Unauthorized active scanning can violate laws and terms of service and may lead to account suspension or legal action.

- Follow responsible disclosure when discovering vulnerabilities or sensitive exposures.
