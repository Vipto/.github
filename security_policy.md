# Security Policy

## 1. Purpose

This document sets out Vipto's security expectations for interns, contributors, and anyone with access to Vipto's repositories or systems, and describes the process for reporting a suspected security vulnerability.

## 2. Responsible Security Behaviour

Everyone with access to Vipto's systems is expected to act as a responsible custodian of that access, using it only for its intended purpose and taking reasonable care to avoid introducing security risk into Vipto's codebase or infrastructure.

## 3. No Unauthorized Repository Access

Access to Vipto repositories is granted on a role-appropriate basis. Attempting to access a repository, branch, or system beyond what has been explicitly granted is not permitted, and any accidental access to information beyond one's authorized scope should be reported rather than used.

## 4. No Credential Sharing

Login credentials, access tokens, and API keys issued to an individual for use with Vipto's systems are personal to that individual and must not be shared with any other person, including other interns or contributors.

## 5. No Committing of Passwords or API Keys

Passwords, API keys, private tokens, and other secrets must never be committed to any Vipto repository, including in code, configuration files, or commit history, regardless of whether the repository is public or private. Any secret required for development should be managed through an appropriate secrets-management mechanism rather than hardcoded.

## 6. Secure Handling of Secrets

Where a contributor is required to work with a secret or credential for development or testing purposes, that secret should be stored securely, used only for its intended purpose, and not transmitted through insecure or informal channels such as unencrypted chat messages containing production credentials.

## 7. Vulnerability Reporting

Any suspected security vulnerability affecting Vipto's application, infrastructure, or repositories should be reported promptly to vipto.app@gmail.com. Vulnerabilities should not be disclosed publicly, including on social media, public GitHub Issues, or third-party forums, prior to acknowledgment and resolution by Vipto.

## 8. Responsible Disclosure

Vipto is committed to working with individuals who report vulnerabilities in good faith, in a manner consistent with responsible disclosure practice. Vipto asks that reporters allow a reasonable period for investigation and remediation before any public disclosure, and that reporters avoid accessing, modifying, or exfiltrating data beyond what is necessary to demonstrate the vulnerability.

## 9. Information to Include in a Security Report

A useful security report should include a clear description of the vulnerability, the steps required to reproduce it, the potential impact if exploited, and any relevant supporting material such as logs or screenshots, excluding any sensitive data that should not be transmitted outside a secure channel.

## 10. Repository Access Management

Repository access is reviewed periodically and is adjusted as roles change, including promptly revoking access for individuals whose engagement with Vipto has concluded. Contributors should notify Vipto if they become aware of access that appears to be outdated or excessive relative to their current role.

## 11. GitHub Security Practices

Contributors are expected to enable appropriate account-level security measures on their own GitHub accounts, including strong authentication, and to follow any repository-level security requirements Vipto has configured, such as branch protection rules on the main development branch, where implemented.

## 12. Incident Escalation

A suspected active security incident — as distinct from a reported vulnerability with no evidence of exploitation — should be escalated immediately to the Engineering Lead and to vipto.app@gmail.com, so that containment and investigation can begin without delay. The handling of confirmed incidents is further described in [`incident-response.md`](./incident-response.md).

## 13. Security Contact

**Email:** vipto.app@gmail.com

## 14. Expected Response Process

Upon receiving a security report, Vipto will acknowledge receipt, assess the reported issue, and communicate with the reporter regarding next steps and expected timelines to the extent practicable, given Vipto's current scale of operations.

## 15. Prohibition on Unnecessary Exploitation

Anyone identifying a potential vulnerability should limit their testing to what is reasonably necessary to confirm and report the issue. Exploiting a vulnerability beyond what is necessary for verification — including accessing, altering, or deleting data — is not authorized and may be treated as a violation of this policy and of applicable law.

## 16. Sensitive Infrastructure Information

This document intentionally does not disclose specific details of Vipto's infrastructure, hosting arrangements, or internal security configuration. Such information is not published publicly and should not be shared outside Vipto's authorized personnel.
