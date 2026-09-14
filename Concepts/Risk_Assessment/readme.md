# 🔐 Cybersecurity Risk Assessment — Beginner Practice

## 📌 Overview

This repository documents my beginner-level learning and practical understanding of **Cybersecurity Risk Assessment**.

The objective of this project is to understand how organizations identify, analyze, prioritize, and mitigate cybersecurity risks.

Risk assessment is an important part of cybersecurity because organizations may have many vulnerabilities, but not every vulnerability has the same level of business impact or urgency.

This project focuses on understanding the relationship between:

**Asset → Threat → Vulnerability → Likelihood → Impact → Risk → Mitigation**

---

# 🎯 Objectives

Through this practice, I aimed to understand:

* What cybersecurity risk means
* What risk assessment is
* Difference between threat and vulnerability
* How likelihood affects risk
* How impact affects risk
* How risk can be prioritized
* How a risk matrix works
* How security controls reduce risk
* What residual risk means
* Why continuous risk monitoring is important

---

# 🧠 What Is Risk Assessment?

Risk assessment is the process of identifying, estimating, and prioritizing risks associated with systems, assets, processes, and operations.

A simple beginner model is:

```text
Risk = Likelihood × Impact
```

The exact methodology can vary between organizations.

---

# 🔎 Key Concepts

## 1. Asset

An asset is something valuable that requires protection.

Examples:

* Database
* Server
* Laptop
* Application
* Customer information
* Credentials
* Source code

---

## 2. Threat

A threat is something that can potentially cause harm.

Examples:

* Cyber attacker
* Malware
* Phishing
* Insider threat
* Natural disaster

---

## 3. Vulnerability

A vulnerability is a weakness that could be exploited.

Examples:

* Outdated software
* Weak passwords
* Missing patches
* Misconfiguration
* Excessive privileges

---

## 4. Likelihood

Likelihood represents how probable it is that a threat will successfully exploit a vulnerability.

Example scale:

```text
1 = Very Low
2 = Low
3 = Medium
4 = High
5 = Very High
```

---

## 5. Impact

Impact represents the potential consequences if the risk occurs.

Example scale:

```text
1 = Very Low
2 = Low
3 = Medium
4 = High
5 = Critical
```

---

# 📊 Risk Calculation

For this beginner exercise:

```text
Risk = Likelihood × Impact
```

Example:

```text
Likelihood = 4
Impact     = 5

Risk = 4 × 5
Risk = 20
```

Therefore, the risk would be considered **Critical** under the scoring model used in this practice.

---

# 📈 Risk Classification

| Score | Risk Level |
| ----: | ---------- |
|   1–4 | Low        |
|   5–9 | Medium     |
| 10–15 | High       |
| 16–25 | Critical   |

> Note: This is an educational scoring model. Organizations may use different risk-rating methodologies.

---

# 🧮 Risk Matrix

| Likelihood / Impact |  1 |  2 |  3 |  4 |  5 |
| ------------------- | -: | -: | -: | -: | -: |
| 5                   |  5 | 10 | 15 | 20 | 25 |
| 4                   |  4 |  8 | 12 | 16 | 20 |
| 3                   |  3 |  6 |  9 | 12 | 15 |
| 2                   |  2 |  4 |  6 |  8 | 10 |
| 1                   |  1 |  2 |  3 |  4 |  5 |

---

# 🧪 Practical Scenario

## Scenario

A company stores customer information in a database.

### Asset

Customer Database

### Threat

External Cyber Attacker

### Vulnerability

Weak Administrator Authentication

### Likelihood

4/5

### Impact

5/5

### Risk Score

```text
4 × 5 = 20
```

### Risk Level

**Critical**

---

# 🛡️ Recommended Mitigation

Possible controls include:

* Multi-Factor Authentication
* Strong password policies
* Least privilege
* Network segmentation
* Encryption
* Patch management
* Logging
* Security monitoring
* Regular vulnerability assessments

---

# 🔄 Residual Risk

After security controls are implemented, some risk may remain.

Example:

```text
Before Mitigation

Likelihood = 4
Impact     = 5

Risk = 20


After Mitigation

Likelihood = 2
Impact     = 5

Residual Risk = 10
```

Residual risk is the remaining risk after security measures have been applied.

---

# 🔁 Risk Assessment Workflow

```text
          ┌───────────────┐
          │ Identify Asset│
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Identify Threat│
          └───────┬───────┘
                  ↓
        ┌───────────────────┐
        │ Identify           │
        │ Vulnerability      │
        └─────────┬─────────┘
                  ↓
          ┌───────────────┐
          │ Assess         │
          │ Likelihood     │
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Assess Impact  │
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Determine Risk │
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Prioritize     │
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Mitigate       │
          └───────┬───────┘
                  ↓
          ┌───────────────┐
          │ Monitor &      │
          │ Reassess       │
          └───────────────┘
```

---

# 🆚 Risk Assessment vs Vulnerability Assessment

| Vulnerability Assessment   | Risk Assessment                                           |
| -------------------------- | --------------------------------------------------------- |
| Finds weaknesses           | Evaluates potential risk                                  |
| Focuses on vulnerabilities | Considers threats, vulnerabilities, likelihood and impact |
| Technical focus            | Technical + business focus                                |
| Produces security findings | Helps prioritize risks                                    |
| Example: outdated software | Example: business impact of exploiting outdated software  |

Both activities can complement each other.

---

# 📋 Sample Risk Register

| ID    | Asset           | Threat   | Vulnerability        | Likelihood | Impact | Risk | Priority | Mitigation               |
| ----- | --------------- | -------- | -------------------- | ---------: | -----: | ---: | -------- | ------------------------ |
| R-001 | Customer DB     | Attacker | Weak Authentication  |          4 |      5 |   20 | Critical | MFA                      |
| R-002 | Web Server      | Attacker | Missing Patch        |          4 |      4 |   16 | Critical | Patch                    |
| R-003 | Employee Laptop | Malware  | Outdated AV          |          3 |      3 |    9 | Medium   | Update Security Software |
| R-004 | Internal App    | Insider  | Excessive Privileges |          2 |      4 |    8 | Medium   | Least Privilege          |

---

# 📚 What I Learned

This practice helped me understand that cybersecurity is not simply about finding vulnerabilities.

A security professional must also understand:

* What is valuable?
* What could attack it?
* What weakness exists?
* How likely is exploitation?
* What would happen if exploitation occurs?
* Which risk should be prioritized?
* What controls can reduce the risk?
* What risk remains after mitigation?

This helped me develop a more **risk-based approach to cybersecurity**.

---

# 🧰 Skills Practiced

* Cybersecurity Risk Assessment
* Risk Identification
* Threat Identification
* Vulnerability Analysis
* Likelihood Assessment
* Impact Assessment
* Risk Scoring
* Risk Prioritization
* Risk Mitigation
* Risk Register Development
* Security Controls
* Residual Risk Analysis
* Security Documentation

---

# 📖 Reference

This practice was developed using concepts from NIST guidance, particularly **NIST SP 800-30 Rev. 1 — Guide for Conducting Risk Assessments**.

NIST explains risk assessment as part of the broader risk-management process and discusses factors such as threats, vulnerabilities, likelihood, impact, and risk responses.

---

# ⚠️ Disclaimer

This repository is an educational cybersecurity practice project.

The examples and scoring model are simplified for learning purposes and should not be treated as a complete enterprise risk assessment methodology.

Organizations may use different frameworks, scoring systems, policies, and risk acceptance criteria.

---

# 🚀 Conclusion

Risk Assessment is a fundamental cybersecurity concept that helps organizations move from:

**"We found a vulnerability."**

to:

**"We understand the potential risk, its priority, and what should be done about it."**

The key concept I am taking from this practice is:

> **Cybersecurity is not only about finding problems — it is about understanding, prioritizing, and managing risk.**

---

## 🔗 Useful NIST Resources

* NIST SP 800-30 — Guide for Conducting Risk Assessments
* NIST Cybersecurity Framework 2.0
* NIST Risk Management Framework

