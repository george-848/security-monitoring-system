# security-monitoring-system
AWS Security Monitoring System# 🛡️ AWS Security Monitoring System

## Overview
This project demonstrates how to build a **Security Monitoring System** on AWS that detects suspicious activities and sends real-time alerts to administrators. The system uses **CloudTrail, CloudWatch, SNS, and Secrets Manager** to automate security monitoring in a scalable and secure way.

---

##  Services Used
- **AWS CloudTrail**: Records and logs all users activities in  .
- **AWS CloudWatch**: Creates metric filters and alarms based on specific CloudTrail events.
- **AWS Secrets Manager**: Securely stores sensitive credentials like API keys or DB passwords and Tokens.
- **Amazon SNS**: Sends notifications (email/SMS) when an alarm is triggered.

---

## 🏗️ Architecture Diagram




## 🚀 How It Works
1. **CloudTrail** records and logs all activities of users who access sensitive credentials
2. **CloudWatch Logs** Creates metric filters and alarms based on specific CloudTrail events..
3. **Metric filters** are created to detect specific patterns (e.g., `secret`, etc.).
4. **Alarms** are triggered when a filter condition is met.
5. **SNS topic** sends an alert to a subscribed email or SMS.
6. **Secrets Manager** ensures secure storage of any sensitive credentials required for integrations.

---

## 📧 Example Alert
```plaintext




