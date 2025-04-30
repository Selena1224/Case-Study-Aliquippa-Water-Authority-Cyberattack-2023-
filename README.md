# Infrastructure Cyber Defense Using Microsoft Defender  
**Case Study: Aliquippa Water Authority Cyberattack (2023)**  
By Soyeong (Selena) Cha | Seattle Pacific University

## Overview
This project analyzes the 2023 cyberattack on the Municipal Water Authority of Aliquippa and proposes a dual-layer defense strategy using Microsoft Defender for Endpoint and Defender for IoT. It includes business impact analysis, tool comparison, and an implementation plan based on cybersecurity principles from the CISSP framework.

## Objective
To demonstrate how a modern, scalable cybersecurity solution can mitigate operational risks in municipal utilities by integrating IT and OT defenses using Microsoft Defender tools.

## Tools and Frameworks
- Microsoft Defender for Endpoint
- Microsoft Defender for IoT
- Microsoft Intune
- CISSP Domains: Security Governance, Network Security, Secure Architecture, Operations

## Key Topics Addressed
- Root causes of the Aliquippa breach (e.g., unsegmented PLCs, default credentials)
- Weaknesses in SCADA/PLC cybersecurity
- Zero Trust and layered defense principles
- Integration of IT/OT monitoring in small utilities

## Repository Contents
- `Project 1 Report.pdf`: Full report with background, analysis, and CISSP alignment
- `Presentation 1 PPT.pptx`: Slide deck for stakeholder presentation
- `Demo Script (optional)`: Walkthrough of detection and containment using Defender tools

## Summary of Findings
- Defender for Endpoint enables real-time threat detection, automated containment, and integration with Microsoft 365.
- Defender for IoT provides passive, agentless monitoring of industrial control systems, ideal for legacy equipment.
- Combined deployment addresses major gaps in municipal infrastructure cybersecurity with cost-effective scalability.

## Implementation Plan Highlights
- Phase 1: Review network layout and identify at-risk PLCs
- Phase 2: Deploy Defender for Endpoint on administrative and control machines
- Phase 3: Deploy Defender for IoT using SPAN/TAP port mirroring
- Phase 4: Tune alert rules and train staff for operational continuity

## Risk Mitigation Strategies
- Address misconfigurations and lack of encryption
- Implement access controls and continuous monitoring
- Reduce false positives and plan for compatibility with legacy systems

## Author
Soyeong (Selena) Cha  
Master’s Student in Data Analytics  
Seattle Pacific University  
[LinkedIn](https://www.linkedin.com/in/selena-cha)

## References
All references, including industry news, academic sources, and Microsoft documentation, are included in the full report.
