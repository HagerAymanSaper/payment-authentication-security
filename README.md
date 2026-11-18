# Beyond the OTP: Investigating Risk-Based Authentication and Security in Online Payment Systems

**Research Project | Cybersecurity | Payment Security**

## Overview

This research investigates the security of online payment authentication mechanisms, focusing on risk-based authentication, EMV 3-D Secure (3DS), and additional verification mechanisms such as One-Time Passwords (OTPs).

The study explores how authentication decisions are made during online card transactions, examines potential weaknesses in authentication workflows, and investigates scenarios in which transactions may proceed without additional verification.

The ultimate goal is to evaluate the security implications of risk-based authentication and develop a controlled environment for studying potential vulnerabilities.

## Problem Statement

Modern online payment systems use risk-based authentication to balance transaction security with user convenience. Depending on transaction risk assessments and issuer policies, some transactions may be authenticated without requiring an additional verification challenge.

Although frictionless authentication is an intended feature of modern payment systems, the security of the underlying authentication decisions, risk assessment mechanisms, and implementation processes deserves further investigation.

This research aims to identify potential weaknesses in these mechanisms and evaluate their security implications through controlled experiments.

## Research Objectives

- Understand online card payment authentication architectures.
- Investigate EMV 3-D Secure authentication flows.
- Examine frictionless and challenge-based authentication.
- Analyze the role of risk-based authentication in transaction approval.
- Identify potential authentication bypass and implementation vulnerabilities.
- Evaluate security weaknesses through controlled simulations.
- Develop recommendations for improving payment authentication security.

## Research Questions

1. How do risk-based authentication mechanisms determine whether additional verification is required?
2. What security differences exist between frictionless and challenge-based 3-D Secure authentication?
3. Under what conditions could weaknesses in authentication implementations allow transactions to proceed without expected verification?
4. How can authentication workflows be evaluated for security weaknesses?
5. What security improvements could reduce the risk of unauthorized transactions?

## Research Scope

The research focuses on:

- EMV 3-D Secure (3DS).
- Risk-Based Authentication (RBA).
- One-Time Password (OTP) verification.
- Frictionless and challenge authentication flows.
- Payment authentication architecture.
- Authentication bypass vulnerabilities.
- Security testing and controlled payment simulations.

Relevant payment ecosystems, including Mastercard and Visa, will be considered where appropriate.

## Proposed Methodology

The research will follow these stages:

1. **Literature Review:** Study payment authentication standards, technical documentation, and existing security research.
2. **Architecture Analysis:** Examine the roles of merchants, payment gateways, issuers, and authentication services.
3. **Threat Modeling:** Identify potential attack surfaces and authentication weaknesses.
4. **Prototype Development:** Build a controlled simulation of merchant, network, and issuer services.
5. **Security Evaluation:** Test authentication scenarios within the controlled environment.
6. **Analysis and Recommendations:** Document findings and propose security improvements.

## Prototype

A simulated payment environment will be developed to investigate authentication workflows without interacting with real payment infrastructure.

Planned components:

- Mock merchant service.
- Simulated payment network.
- Mock card issuer.
- Authentication decision engine.
- OTP and 3-D Secure flow simulation.
- Security testing and logging components.

Implementation details and technical documentation will be maintained in the `/prototype` directory.

## Ethical Considerations

All experiments will be conducted within an isolated, controlled environment using simulated payment services and test data.

No unauthorized testing against real payment platforms, financial institutions, card networks, or merchant systems will be performed.

This research is independent and is not affiliated with Mastercard, Visa, or any financial institution.

## Project Structure

```text
payment-authentication-security/
│
├── README.md
├── LICENSE
├── CITATION.cff
├── .gitignore
│
├── docs/
│   ├── README.md
│   ├── literature-review/
│   ├── research-design/
│   └── diagrams/
│
└── prototype/
    └── README.md
```

## Current Status

**Status:** Work in Progress  
**Started:** 2026-11-18

The project is currently in its initial research and documentation phase.

## Author

**Hager Ayman Saper**

Cybersecurity Researcher

GitHub: [HagerAymanSaper](https://github.com/HagerAymanSaper)

---

This repository documents the research process, technical development, experimental results, and findings.
