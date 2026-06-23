# Security Policy

## Supported Versions

The following versions of the Lilith Intelligence Platform currently receive security updates and vulnerability remediation support.

| Version                  | Supported          |
| ------------------------ | ------------------ |
| Current Release (v2.x)   | ✅                  |
| Release Candidates (RC)  | ⚠️ Limited Support |
| Legacy Versions (< v2.0) | ❌                  |

Only the latest production release receives full security maintenance.

---

# Responsible Disclosure

The Lilith Intelligence Platform team welcomes responsible disclosure of legitimate security vulnerabilities.

Do not publicly disclose vulnerabilities until remediation has been completed and authorization has been granted.

---

# How to Report a Vulnerability

Submit reports through:

* GitHub Security Advisories (preferred)
* Private security reporting email
* Designated security portal (if available)

Please include:

* Vulnerability description
* Affected component
* Reproduction steps
* Proof-of-Concept (PoC)
* Impact assessment
* Screenshots, logs, or evidence where applicable

Reports lacking sufficient evidence may be closed without action.

---

# Scope

### In Scope

* Authentication mechanisms
* Authorization controls
* Session management
* API security
* Data exposure vulnerabilities
* Business logic flaws
* Cloud deployment components
* Evidence handling systems
* Validation workflows
* Workspace isolation controls

### Out of Scope

The following are generally not considered security vulnerabilities:

* Missing security headers without exploitability
* Self-XSS
* Social engineering attacks
* Physical attacks
* Denial of Service testing
* Automated scanner output without validation
* Vulnerabilities requiring local administrator access
* Third-party dependency issues without demonstrable impact
* Theoretical attacks without reproducible evidence

---

# Safe Harbor

Security researchers acting in good faith and within authorized testing boundaries will not be subject to legal action by the project maintainers.

Researchers must:

* Avoid service disruption
* Avoid accessing unauthorized data
* Avoid privilege escalation beyond proof requirements
* Avoid persistence mechanisms
* Avoid destructive testing

Testing must remain non-destructive and evidence-driven.

---

# Disclosure Process

1. Report received
2. Initial triage
3. Validation and reproduction
4. Severity assessment
5. Remediation planning
6. Patch development
7. Security advisory publication
8. Public disclosure

---

# Response Timeline

| Action                  | Target Time       |
| ----------------------- | ----------------- |
| Initial Acknowledgement | 72 Hours          |
| Triage Decision         | 7 Days            |
| Validation Outcome      | 14 Days           |
| Remediation Target      | Based on Severity |

Complex vulnerabilities may require additional investigation time.

---

# Severity Classification

### Critical

* Remote Code Execution
* Authentication Bypass
* Cross-Tenant Compromise
* Privilege Escalation to Administrative Control

### High

* Account Takeover
* Sensitive Data Exposure
* Significant Authorization Failures

### Medium

* Limited Information Disclosure
* Partial Security Control Bypass

### Low

* Security Hardening Recommendations
* Minor Information Leakage

---

# Platform Security Principles

Lilith operates under a Validation-First Security Model:

* Findings require evidence
* Autonomous detections are not treated as confirmed vulnerabilities
* Validation workflows require reproducible proof
* Promotion of findings requires verification
* Human review remains the final authority for public disclosure

---

# Bounty Program

Unless explicitly announced, Lilith does not currently operate a public bug bounty program.

Security reports are accepted through responsible disclosure channels only.

---

# Contact

Security Contact:
[security@your-domain.com](mailto:security@your-domain.com)

GitHub Security Advisories:
https://github.com/<organization>/<repository>/security/advisories
