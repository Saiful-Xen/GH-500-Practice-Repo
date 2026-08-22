# GH-500 GitHub Advanced Security Practice Lab

This repository is created as a hands-on practice environment for the
**GitHub Advanced Security (GH-500) certification**.

The purpose of this repository is to provide a practical environment to
understand, configure, test, and remediate security issues using GitHub
Advanced Security features.

## 🎯 Objectives

The main objectives of this lab are to gain practical experience with:

- GitHub Advanced Security
- CodeQL
- Code Scanning
- Secret Scanning
- Push Protection
- Dependabot
- Dependency Review
- Security Advisories
- Private Vulnerability Reporting
- GitHub Actions security
- Repository security policies
- Branch protection and rulesets
- Security alerts and remediation
- Security Overview
- Security configuration and administration

## 🔐 GitHub Security Features

This repository is intended to be configured with the following GitHub
security features:

### 1. Code Scanning

Use CodeQL to identify security vulnerabilities and coding errors.

Practice:

- Enabling CodeQL
- Configuring CodeQL workflows
- Running CodeQL analysis
- Reviewing code scanning alerts
- Understanding alert severity
- Understanding CWE information
- Reviewing data flow
- Fixing vulnerabilities
- Verifying remediation

### 2. Secret Scanning

Practice identifying accidentally committed secrets and sensitive
credentials.

Practice:

- Secret scanning
- Secret scanning alerts
- Push Protection
- Alert remediation
- Secret revocation
- Alert dismissal and resolution

> Only dummy/test credentials should be used in this repository.

### 3. Dependabot

Practice identifying vulnerable dependencies.

Practice:

- Dependency Graph
- Dependabot alerts
- Dependabot security updates
- Version updates
- Reviewing Dependabot pull requests
- Updating vulnerable packages

### 4. Dependency Review

Practice identifying vulnerable dependencies introduced through pull
requests.

Practice:

- Creating a pull request
- Introducing a vulnerable dependency
- Running Dependency Review
- Reviewing dependency changes
- Blocking or remediating risky dependencies

### 5. GitHub Actions Security

Practice securing CI/CD workflows.

Practice:

- Workflow permissions
- `GITHUB_TOKEN` permissions
- Least-privilege permissions
- Third-party actions
- Action version pinning
- Workflow security
- Pull request security considerations

### 6. Security Advisories

Practice the GitHub vulnerability management workflow.

Practice:

- Creating a security advisory
- Private vulnerability reporting
- Reviewing vulnerability information
- Assigning severity
- Remediation
- Publishing security information

### 7. Repository Security Controls

Practice configuring repository-level security controls.

Practice:

- Branch protection
- Repository rulesets
- Required status checks
- Pull request reviews
- Code scanning requirements
- Security policies

## 📂 Repository Structure

```text
gh500-security-lab/
│
├── src/
│   ├── app.py
│   ├── api.py
│   ├── auth.py
│   └── database.py
│
├── tests/
│   └── test_app.py
│
├── .github/
│   ├── workflows/
│   │   ├── codeql.yml
│   │   └── dependency-review.yml
│   │
│   └── dependabot.yml
│
├── requirements.txt
├── SECURITY.md
└── README.md
