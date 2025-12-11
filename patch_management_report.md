# Patch Management Report
# Task 6 – Oasis Infobyte Cybersecurity Internship
# Prepared by: Rajesh Nandi
# 1. Introduction

Patch management is a crucial security process that involves identifying, acquiring, testing, and installing updates (patches) for software, operating systems, and applications.
These patches fix vulnerabilities, improve performance, and add new features.

In modern cybersecurity, patch management is essential for reducing the attack surface and preventing exploitation by malicious actors.

# 2. What is Patch Management?

Patch management is the structured process of:

Monitoring systems for available patches

Evaluating the risk and impact of each patch

Testing patches in a controlled environment

Deploying patches across systems

Verifying successful installation

A “patch” is a piece of code released by software vendors to:

✔ Fix security vulnerabilities
✔ Resolve bugs
✔ Enhance functionality
✔ Improve stability and performance

# 3. Why Patch Management is Important in Cybersecurity
# 3.1 Prevents Exploitation of Known Vulnerabilities

Most cyberattacks exploit publicly known vulnerabilities.
Example:

WannaCry ransomware attack exploited the unpatched EternalBlue vulnerability (CVE-2017-0144).

Organizations that applied patches were immune; those that didn’t were compromised.

# 3.2 Reduces Attack Surface

Unpatched systems leave unnecessary open doors for attackers.
Patching reduces the number of exploitable entry points.

# 3.3 Enhances System Stability

Patches do more than security:

Fix software bugs

Improve compatibility

Increase overall system reliability

# 3.4 Ensures Compliance and Avoids Penalties

Regulatory standards require up-to-date patch levels:

PCI-DSS

HIPAA

ISO 27001

Failing to patch may result in legal consequences and financial penalties.

# 3.5 Protects Sensitive Data

Unpatched systems can leak:

Credentials

Customer data

Business secrets

A single unpatched vulnerability can compromise the entire organization.

# 4. Consequences of Failing to Apply Patches
# 4.1 Increased Vulnerability to Cyberattacks

Attackers continuously scan the internet for systems missing critical patches.

# Examples:

Equifax Breach (2017): Unpatched Apache Struts vulnerability led to a massive data breach affecting 147 million people.

WannaCry Ransomware (2017): Hundreds of thousands of systems infected due to missing Microsoft patch MS17-010.

# 4.2 Financial Losses

Unpatched systems can lead to:

Ransomware payments

Business downtime

System rebuild costs

Compliance fines

Cost of breach > Cost of patching.

# 4.3 Data Breaches and Loss of Trust

Loss of sensitive data can damage:

Brand reputation

Customer trust

Business relationships

# 4.4 System Instability and Crashes

Old, unpatched software tends to:

Crash more often

Break dependencies

Cause operational delays

4.5 Spread of Malware Across Networks

Unpatched endpoints can spread malware laterally within an organization.

# 5. Best Practices for Effective Patch Management
# 5.1 Maintain an Inventory of All Assets

Know what software and systems you have:

Operating systems

Applications

Cloud services

Network devices

You cannot patch what you do not track.

# 5.2 Enable Automatic Updates Where Appropriate

For routine updates, enabling automation reduces human effort and delays.

# 5.3 Regularly Monitor for New Patches

Use tools like:

Microsoft WSUS

SCCM

Tenable Nessus

Qualys

OpenVAS

This ensures timely awareness of emerging vulnerabilities.

# 5.4 Test Patches Before Deployment

Testing prevents system outages caused by incompatible updates.

# 5.5 Prioritize Critical Security Patches

Rating scales:

Critical → patch immediately

High → patch within a few days

Medium/Low → schedule within maintenance window

# 5.6 Document and Track Patch Status

Maintain logs of:

Installed patches

Failed patches

Systems pending updates

This supports auditing and compliance.

# 5.7 Use Centralized Patch Management Tools

# Examples:

WSUS / SCCM

ManageEngine Patch Manager

SolarWinds Patch Manager

Central control improves efficiency.

# 5.8 Train Staff & Build Awareness

Human factors matter — employees should understand:

Why patches matter

How to follow update policies

# 6. Conclusion

Patch management is a fundamental part of cybersecurity.
Ignoring patches leaves systems open to attacks, data breaches, and operational failures.

Organizations that implement strong patch management enjoy:

✔ Improved security
✔ Enhanced stability
✔ Regulatory compliance
✔ Reduced risk of exploit-based attacks

Patch management is not optional — it is essential for protecting systems in today’s threat landscape.
