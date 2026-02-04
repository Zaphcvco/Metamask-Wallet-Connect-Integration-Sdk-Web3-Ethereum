# Security Policy

## Supported Versions

We actively support the latest version of BlockchainBridge with security updates. For older versions, security updates are provided on a best-effort basis.

| Version | Supported          |
| ------- | ------------------ |
| Latest  | :white_check_mark: |
| < Latest| :warning:         |

## Reporting a Vulnerability

We take security vulnerabilities seriously. If you discover a security vulnerability in BlockchainBridge, please follow these steps:

### How to Report

1. **Do not** open a public GitHub issue for security vulnerabilities.
2. Email security details to the maintainers at the repository owner's contact (or create a private security advisory through GitHub).
3. Include the following information in your report:
   - Description of the vulnerability
   - Steps to reproduce the issue
   - Potential impact
   - Suggested fix (if available)

### What to Expect

- **Initial Response:** We will acknowledge receipt of your report within 48 hours.
- **Status Updates:** You will receive updates on the status of the vulnerability within 7 days of the initial report.
- **Resolution Timeline:** Critical vulnerabilities will be addressed as quickly as possible. We aim to provide a fix or mitigation within 30 days for high-severity issues.
- **Disclosure:** We will coordinate with you on the disclosure timeline. We typically disclose vulnerabilities after a fix has been released.

### Scope

This security policy applies to:
- The BlockchainBridge library code
- Security issues related to MetaMask integration
- Vulnerabilities in dependencies that affect BlockchainBridge functionality

### Out of Scope

The following are considered out of scope for security reporting:
- Issues in MetaMask itself (please report to MetaMask)
- Issues in third-party services or APIs used by applications built with BlockchainBridge
- Social engineering attacks
- Denial of service attacks that don't compromise security

## Security Best Practices

When using BlockchainBridge:
- Always verify transaction details before signing
- Use HTTPS in production environments
- Keep dependencies up to date
- Review and audit smart contracts before deployment
- Follow MetaMask security guidelines

Thank you for helping keep BlockchainBridge and its users safe!
