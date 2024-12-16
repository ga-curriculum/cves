<h1>
  <span class="headline">CVEs</span>
  <span class="subhead">What Are CVEs and Why Are They Important</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to define common Vulnerabilities and Exposures (CVEs) and explain their role in identifying security risks.

## Introduction

### Scenario: A Compromised Server

Imagine your company's server is suddenly compromised. The IT team realized it was because of an unpatched vulnerability.

**How could this have been prevented?**

- By understanding how to use the CVE system to discuss and prioritize risks.
- By proactively identifying and addressing the vulnerability.

## What are CVEs?

CVE stands for ***Common Vulnerabilities and Exposures***. It's a catalog of publicly disclosed cybersecurity vulnerabilities maintained by [MITRE Corporation](https://www.mitre.org/who-we-are).

Tens of thousands of CVE records are being maintained. You can access the catalog online at [https://cve.mitre.org/](https://cve.mitre.org/).

- CVEs provide a standardized reference for discussing common vulnerabilities.
- They also help organizations prioritize and address risks systematically.

To get a brief example of a CVE, [search the CVE list for `CVE-2021-34527`](https://www.cve.org/CVERecord?id=CVE-2021-34527): This is a known Windows Print Spooler Vulnerability (***aka "PrintNightmare"***) that allows attackers to execute malicious code on an affected system.

## Why CVEs Matter

As we become familiar with CVEs and understand what they are, you might wonder why they matter and what makes them essential.

CVEs are a critical tool used to identify and understand security risks. They provide organizations with the information needed to protect their systems and data by proactively addressing vulnerabilities before they become exploited.

## The Role of CVEs in Identifying Security Risks

CVEs play a crucial role in the process of identifying security risks; here's a brief outline of how security professionals use them:

- **Identify Vulnerabilities**: Security teams use CVE entries to identify weaknesses in their systems or software.
- **Assess Risk**: Each CVE entry includes a detailed description and often a CVSS (Common Vulnerability Scoring System) score that measures severity.
- **Prioritize Action**: High-severity CVEs, especially actively exploited ones, are prioritized for immediate action.

## Wrap-Up: High-Level Review

Now that we've had a chance to discuss the what, why, and how of CVEs, let's wrap up this section by reviewing a typical workflow to conceptualize this process:

1. IT identifies a vulnerability in outdated software via its CVE entry.
2. The CVE details are used to determine the scope of the threat.
3. A patch or workaround is implemented to reduce the risk.
