# NIST CSF Incident Response Analysis

## Overview

This project analyzes a denial of service (DoS) attack against a multimedia company using the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF).

The investigation focuses on identifying the attack, assessing impacted systems, implementing security improvements, and developing detection, response, and recovery strategies.

## Objective

- Analyze a DoS attack involving ICMP flooding
- Apply the NIST Cybersecurity Framework (CSF)
- Identify security weaknesses
- Improve network protection and monitoring
- Develop incident response and recovery plans

## Attack Summary

The organization experienced a denial of service (DoS) attack caused by a flood of incoming ICMP packets entering through an improperly configured firewall.

The attack disrupted internal network operations for approximately two hours and prevented normal access to network resources.

## Security Improvements Implemented

- Firewall ICMP rate limiting
- Source IP verification
- Network traffic monitoring
- IDS/IPS deployment

## Project Structure

- incident-summary.md
- identify.md
- protect.md
- detect.md
- respond.md
- recover.md
- recommendations.md

## Outcome

The project applies the NIST CSF framework to improve network security, incident response readiness, monitoring capabilities, and recovery planning after a DoS attack.

## References

- [Incident Report Analysis Template](docs/incident-report-analysis-template.pdf)

- [Incident Report Analysis Example](docs/incident-report-analysis-example.pdf)

- [Applying the NIST CSF](docs/applying-nist-csf.pdf)
