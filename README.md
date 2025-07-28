# Company Network Merger – Zero Trust Architecture

## Overview
This project documents the secure integration of two enterprise networks Company A and Company B into a unified, modernized infrastructure. The solution prioritizes Zero Trust architecture, cloud-first design, and identity-based access control using Okta, Cloud RADIUS, and Amazon Web Services (AWS).

This project was completed as part of the Master of Science in Cybersecurity and Information Assurance program at Western Governors University (WGU).

## Objective
Design and document a secure, compliant, and cost-effective network merger that:
- Eliminates legacy, end-of-life systems
- Enables centralized identity and access management
- Implements network segmentation for both wired and wireless environments
- Leverages AWS-native services to reduce on-premises infrastructure
- Operates within a $50,000 implementation budget

## Key Features
- Zero Trust Network Architecture applied across the environment
- Okta SSO and MFA for centralized identity federation
- Cloud RADIUS for wireless authentication and device-based access control
- FortiGate next-generation firewall and VLAN segmentation
- AWS services including RDS, FSx, Elastic Beanstalk, and Transfer Family
- Continuous monitoring and logging with AWS CloudTrail and GuardDuty
- Full decommissioning of unsupported systems such as Windows 7 and legacy Cisco equipment

## Documentation Included
The repository includes the following documentation:
- Source documents from both companies, including network diagrams and risk reports
- Final merged network diagram
- Written technical documentation:
  - Business requirements and goals
  - Identified network and infrastructure issues
  - Detailed Zero Trust design implementation
  - Compliance and regulatory considerations
  - Budget allocation and resource summary
  - Configuration guides for Okta, Cloud RADIUS, and AWS routing

## Compliance Considerations
The design adheres to security principles derived from HIPAA and PCI-DSS frameworks. All access is identity-bound and based on least privilege, with layered security controls and centralized audit logging to support policy enforcement and incident response.

## Credit
This project was completed in fulfillment of academic requirements at Western Governors University. All analysis, architecture, and documentation reflect original work by Bryce Hansen.
