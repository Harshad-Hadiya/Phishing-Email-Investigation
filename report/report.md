# Phishing Email Investigation Report

## Objective

The objective of this investigation was to analyze a suspicious email and determine whether it was a legitimate Microsoft notification or a phishing attempt.

## Email Information

Subject: Microsoft account security alert

Sender: support@office-365-notifications[.]com

Purported Organization: Microsoft

## Analysis

### Sender Analysis

The sender domain `office-365-notifications[.]com` is not an official Microsoft-owned domain. Legitimate Microsoft emails are typically sent from domains such as `microsoft.com`, `office.com`, or `outlook.com`.

### Content Analysis

The email warns that someone has accessed the recipient's Microsoft account and requests immediate action. Such messages are commonly used in phishing campaigns to create panic and pressure users into clicking malicious links.

### Social Engineering Indicators

* Use of urgency and fear
* Account compromise warning
* Immediate recovery request
* Trusted brand impersonation

### Link Analysis

The email contains a "Recover Account" button that may redirect users to a malicious website designed to collect Microsoft account credentials.

## Threat Assessment

Threat Level: High

Attack Type: Credential Phishing

Potential Impact:

* Account compromise
* Unauthorized access
* Data theft
* Business email compromise

## Recommendations

1. Do not click any links or buttons in the email.
2. Verify the sender domain before taking action.
3. Report the email to the security team.
4. Block the sender domain if confirmed malicious.
5. Enable Multi-Factor Authentication (MFA).
6. Conduct user awareness training on phishing attacks.

## Conclusion

The investigation identified multiple phishing indicators, including domain impersonation, urgency-based social engineering, and a potential credential harvesting attempt. Based on these findings, the email is classified as a phishing email and should be reported and blocked.
