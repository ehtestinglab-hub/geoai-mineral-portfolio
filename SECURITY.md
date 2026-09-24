# Security Policy

## Supported scope

This repository is a public technical portfolio containing reproducible GeoAI and geospatial data science examples.

Security reports are relevant when they concern:

- accidental exposure of credentials, tokens, or private keys;
- sensitive or confidential information committed to the repository;
- dependency or configuration issues that could create a meaningful security risk;
- code or workflow behaviour that could expose a user's local environment or data;
- vulnerabilities in reusable code included in this repository.

General modelling errors, scientific disagreements, feature requests, and documentation corrections are not security vulnerabilities and may be reported through the normal issue tracker.

## Reporting a vulnerability

Please do not disclose suspected security vulnerabilities in a public GitHub issue.

After this repository is published, use GitHub's private vulnerability reporting mechanism when available.

If private vulnerability reporting is not available, contact the repository maintainer through the GitHub profile associated with this project before publicly disclosing the issue.

When reporting a vulnerability, please include:

- a concise description of the issue;
- the affected file or component;
- steps required to reproduce the issue;
- the potential impact;
- any suggested mitigation, if known.

Do not include real credentials, private keys, proprietary datasets, or other sensitive information in the report.

## Repository security practices

The repository uses several preventive controls, including:

- `.gitignore` rules for credentials, environment files, caches, and private data;
- pre-commit validation;
- Gitleaks secret scanning;
- automated tests for reusable code;
- reproducible dependency definitions;
- signed Git commits where applicable;
- Pull Request based integration;
- separation between public portfolio material and non-public development work.

Credentials, API keys, private keys, proprietary datasets, and sensitive configuration must never be committed to this repository.

## Dependency security

Dependencies are introduced incrementally and are defined through the reproducible project environment.

Security-related dependency updates may be applied when they are compatible with the validated scientific environment.

## Disclosure

Please allow reasonable time for investigation and remediation before public disclosure of a confirmed vulnerability.

The objective is to resolve legitimate security issues while preserving reproducibility and traceability of the portfolio.
