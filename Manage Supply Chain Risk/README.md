# Manage Supply Chain Risk

## Project Overview 
This project focused on assessing and mitigating risks within the PeoplePro Suite, a third-party software solution under consideration by Monistax. 
The assessment identified critical vulnerabilities and compliance gaps, offering recommendations to secure the supply chain and align with Monistax’s stringent security policies.

## Key Objectives 
1. <strong>Conduct a risk assessment </strong> to evaluate operational risks and vulnerabilities within the software.
2. <strong>Identify compliance gaps</strong> between the PeoplePro Suite and Monistax’s security requirements.
3. <strong>Provide actionable recommendations</strong> to mitigate risks and improve the software’s security posture.

## Risk Assessment Summary 
### Key Identified Risks
1. <strong>Phishing Attacks:</strong> Credential theft leading to unauthorised system access.
2. <strong>SQL Injection Vulnerabilities:</strong> Exploitable flaws unauthorised  database access.
3. <strong>Outdataed Software:</strong> Unpatched systems susceptible to exploitation.
4. <strong>Weak Encryption:</strong> Insufficient data protection mechanisms.
5. <strong>Insider Threats:</strong> Legitimate access misused for malicious purposes.

### High-Risk Scenarios

- <strong>Financial Fraud:</strong> Credential theft leading to unauthorised system access.
- <strong>Data Breaches:</strong> Leakage of sensitive payment and personal infomation.
- <strong>Incident Response Delays:</strong> Prolonged system exploitation due to slow response.

## Deliverables
### 1. Risk Assessment Report
A comprehensive evaluation of risks, including:
- <strong>Likelihood and Impact Analysis:</strong> Quantifying risk severity to prioritise remediation.
- <strong>Compliance Assessment:</strong> Identifying gaps between Monistax policies and software security.

### 2. Recommendations
Immediate measures such as:
- Implementing multi-factor authentication (MFA).
- Strengthening encryption practices (AES-256 for data at rest, TLS 1.2+ for transit).
- Enhancing incident response planning.

Mid-to-long-term actions including:
- Regular vulnerability scans.
- API security audits.
- Segmentation of network infrastructure to prevent lateral movement.

## Methodology 

1. <strong>Data Gathering:</strong> Reviewed software documentation, security scans, and Monistax policies.
2. <strong>Risk Evaluation:</strong> Assessed the likelihood and impact of various attack paths.
3. <strong>Compliance Mapping:</strong> Compared software capabilities against Monistax’s policies.
4. <strong>Prioritisation:</strong> Ranked risks by severity using a structured risk matrix.

## Findings and Recommendations
### Risk Matrix Summary 

| Scenario                        | Likelihood | Impact   | Severity | Acceptance Level       |
|---------------------------------|------------|----------|----------|------------------------|
| Financial Fraud                 | High       | Critical | **12**   | **Unacceptable**       |
| SQL Injection                   | High       | Serious  | **9**    | Tolerable under control|
| Phishing                        | High       | Serious  | **9**    | Tolerable under control|
| Weak Encryption                 | High       | Serious  | **9**    | Tolerable under control|
| Outdated Software/No Backups    | Medium     | Serious  | **6**    | Tolerable under control|
| Insider Threats                 | Medium     | Serious  | **6**    | Tolerable under control|

### Immediate Recommendations
1. <strong>MFA Implementation:</strong> Strengthen user authentication mechanisms.
2. <strong>Encryption Standards:</strong> Ensure compliance with AES-256 and TLS 1.2+.
3. <strong>Incident Response Plan:</strong> Develop and test robust response protocols.

### Long-Term Recommendations
- Regular software updates and backup protocols.
- Segmentation of network infrastructure to limit lateral movement.

## Compliance Gaps and Solutions
### Key Gaps 
- SQL injection vulnerabilities.
- Inadequate encryption practices.
- Missing documentation on logging and monitoring.

### Proposed Actions
- Implement parameterised queries to address SQL injection.
- Conduct encryption audits and update practices.
- Establish comprehensive logging and monitoring protocols.

## Lessons Learned 
1. The importance of proactive risk management in securing supply chains.
2. Aligning third-party solutions with organisational security polocies.
3. Continuous monitoring and updates to mitigate evolving risks.

## Files in This Repository 
### Reports 
### Analysis 

## Acknowledgments
