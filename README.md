# Penetration Testing Report for NBN Corp

Note: NBN Corp and the organizational details mentioned in this repository are entirely fictional and were created solely for the purposes of a course project.

This repository contains the documentation and findings of a penetration test conducted on NBN Corporation's digital assets. The test was carried out by SentinelSec Solutions as part of a cybersecurity initiative to identify vulnerabilities in NBN's external-facing web server and client machine. The documents provided summarize the methodology, findings, and recommendations for securing the network.

## Documents

1. **Avinash Narasimhan - Final Project.pdf**:
   - Comprehensive penetration testing report for NBN Corp.
   - Includes the test methodology, findings, risk assessments, and recommendations.
   - Highlights major vulnerabilities such as anonymous FTP login, XSS attacks, and privilege escalation.
   - Details the risk scoring using CVSS and provides actionable remediation steps.

2. **Final Project.pdf**:
   - Overview of the penetration testing challenge and context.
   - Provides the objectives, constraints, and setup instructions for the test environment.
   - Includes guidelines for methodology, grading rubric, and additional details about the testing scenario.

## Key Findings

- **High-Risk Vulnerabilities**:
  - Anonymous FTP login allowing unauthorized access.
  - Cross-Site Scripting (XSS) attacks, both persistent and reflected.
  - Remote OS command injection.
  - Privilege escalation on both server and client machines.

- **Risk Scores**:
  - Assessed using the CVSS framework.
  - Highest risk score: 9.6 (Privilege escalation to root).

- **Recommendations**:
  - Disable anonymous FTP login and enforce strict password policies.
  - Sanitize inputs to prevent XSS and injection attacks.
  - Update and patch vulnerable services like `pkexec`.

## Purpose

The goal of this project is to simulate a real-world red-team penetration test to identify and mitigate potential cybersecurity risks. These findings aim to help NBN Corp secure its digital assets against external threats.

For more information, refer to the detailed reports in this repository.
