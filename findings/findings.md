# Findings

## Phishing Indicators Identified

### 1. Suspicious Sender Domain

The email was sent from `support@office-365-notifications[.]com`, which is not an official Microsoft domain.

### 2. Brand Impersonation

The attacker impersonated Microsoft by using Microsoft branding and a security alert theme to gain user trust.

### 3. Urgency and Fear Tactics

The email claims that someone has accessed the user's account, creating urgency and encouraging immediate action.

### 4. Credential Harvesting Attempt

The "Recover Account" button may redirect users to a fake login page designed to steal credentials.

### 5. Social Engineering

The email uses psychological manipulation to convince the recipient to act without verifying the legitimacy of the message.

## Risk Assessment

Risk Level: High

Category: Credential Phishing

## Indicators of Compromise (IOCs)

* Sender: support@office-365-notifications[.]com
* Subject: Microsoft account security alert
* Attack Type: Phishing
* Target: Microsoft 365 Users

## Conclusion

Based on the sender domain, impersonation techniques, urgency-based language, and credential theft indicators, this email has been classified as a phishing email.
