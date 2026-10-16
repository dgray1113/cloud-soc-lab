# Cloud-Based Windows SOC Lab

## Overview

This project builds a cloud-hosted Security Operations Center (SOC) lab using virtual machines and security monitoring tools. The goal is to practice security log collection, threat detection, incident investigation, and incident documentation in a controlled environment.

## Objectives

- Deploy and manage virtual machines in a cloud environment.
- Collect and analyze Windows security events.
- Detect suspicious authentication activity and other security-relevant events.
- Investigate alerts and document findings.
- Develop and test detection rules.
- Document the architecture, implementation, and results.

## Planned Architecture

- **Cloud infrastructure:** Virtual machines and networking.
- **Endpoint:** Windows virtual machine generating security telemetry.
- **Monitoring:** Log collection and SIEM or other security analytics tooling.
- **Detection:** Queries and rules for identifying suspicious activity.
- **Documentation:** Investigation reports, evidence, and lessons learned.

## Repository Structure

- `docs/` - Architecture, setup instructions, and technical notes.
- `detections/` - Detection rules and queries.
- `investigations/` - Incident investigation reports.
- `evidence/` - Sanitized screenshots and sample logs.
- `infrastructure/` - Cloud infrastructure configuration.
- `scripts/` - Automation and test-event generation scripts.

## Cost and Security Considerations

The lab will prioritize free-tier or low-cost cloud resources. Cloud services will be checked for potential charges before deployment. Test activity will be restricted to systems I own or am authorized to use. No credentials, secrets, or sensitive organizational data will be committed to this repository.

## Project Status

Planning and repository setup. Architecture, infrastructure, detections, and investigation reports will be added as the lab is implemented.
