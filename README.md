# Banking System - Software System Analysis

This repository contains the software system analysis for a Banking System. It documents the system's purpose, functional and non-functional requirements, risks, and potential AI integrations based on the provided specifications.

## Project Details
* **Name:** Muhammad Usman Waheed[cite: 2]
* **Roll No:** 2025-SE-278[cite: 2]
* **Class:** BS Software Engineering Fall Afternoon - B[cite: 2]
* **Subject:** Software Engineering[cite: 2]

## A. Purpose
A Banking System is a software platform that enables financial institutions to manage customer accounts, process transactions, and deliver banking services securely and efficiently[cite: 2]. Its core purpose is to automate financial operations such as deposits, withdrawals, transfers, loan processing, and account management while ensuring accuracy, regulatory compliance, and data security across all operations[cite: 2].

## B. Users
* **Retail customers:** Individuals managing personal accounts, transfers, and payments[cite: 2].
* **Corporate/business clients:** Companies managing payroll, bulk transactions, and trade finance[cite: 2].
* **Bank tellers/staff:** Employees performing in-branch transactions[cite: 2].
* **Bank administrators:** Manage system configuration, user roles, and permissions[cite: 2].
* **Loan officers:** Process and approve loan applications[cite: 2].
* **Auditors/compliance officers:** Review transactions for regulatory adherence[cite: 2].

## C. Stakeholders
* Bank management and executives[cite: 2]
* Shareholders/investors[cite: 2]
* Regulatory bodies (e.g., central banks, financial authorities)[cite: 2]
* IT/software development and support teams[cite: 2]
* Third-party service providers (payment gateways, credit bureaus)[cite: 2]
* End customers (retail and corporate)[cite: 2]

## D. Functional Requirements
1. The system shall allow users to create, view, update, and close bank accounts[cite: 2].
2. The system shall process deposits, withdrawals, and fund transfers between accounts[cite: 2].
3. The system shall generate account statements and transaction histories[cite: 2].
4. The system shall support loan application submission, approval workflows, and repayment tracking[cite: 2].
5. The system shall authenticate users via secure login (e.g., multi-factor authentication) before granting access[cite: 2].

## E. Non-Functional Requirements
1. **Security:** All transactions and data must be encrypted (e.g., AES-256, TLS) both in transit and at rest[cite: 2].
2. **Availability:** The system shall maintain 99.9% uptime to support 24/7 banking operations[cite: 2].
3. **Performance:** Transaction processing shall complete within 2-3 seconds under normal load[cite: 2].
4. **Scalability:** The system shall support a growing number of concurrent users without performance degradation[cite: 2].
5. **Regulatory Compliance:** The system shall comply with financial regulations such as PCI-DSS, KYC, and AML standards[cite: 2].

## F. Risks
1. **Cybersecurity threats:** Data breaches, phishing, or fraud attacks could compromise sensitive financial data[cite: 2].
2. **System downtime:** Outages could disrupt critical banking services, causing financial and reputational loss[cite: 2].
3. **Regulatory non-compliance:** Failure to meet evolving financial regulations could result in legal penalties[cite: 2].

## G. Quality Attributes
1. **Reliability:** The system must consistently perform accurate transactions without failure[cite: 2].
2. **Security:** Strong protection of sensitive financial and personal data is essential[cite: 2].
3. **Usability:** The interface must be intuitive for users across varying levels of technical literacy[cite: 2].

## H. AI Integration
**Where AI Could Be Used:**
* **Fraud detection:** AI models can analyze transaction patterns in real time to flag suspicious activity[cite: 2].
* **Credit scoring:** Machine learning can assess loan applicants' creditworthiness more accurately[cite: 2].
* **Chatbots/virtual assistants:** AI-powered support for customer queries and basic transactions[cite: 2].
* **Personalized financial recommendations:** AI can suggest savings plans or investment products based on user behavior[cite: 2].

**What Could Go Wrong If AI Is Used Incorrectly:**
* **Biased decision-making:** Poorly trained AI models could unfairly deny loans or flag legitimate transactions based on biased data[cite: 2].
* **False positives/negatives in fraud detection:** Legitimate transactions could be blocked, or actual fraud could go undetected, damaging trust[cite: 2].
* **Lack of transparency (black-box decisions):** Customers and regulators may be unable to understand why an AI made a specific decision, raising accountability and compliance concerns[cite: 2].
