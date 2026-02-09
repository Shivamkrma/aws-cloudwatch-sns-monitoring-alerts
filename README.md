This project implements a cloud-based monitoring and alerting system using AWS CloudWatch and Amazon SNS.
It continuously monitors EC2 instance performance metrics and sends real-time email alerts when predefined thresholds are breached.Overview

This project implements a cloud monitoring and alerting solution using AWS CloudWatch and Amazon SNS. It monitors EC2 instance performance and automatically sends email alerts when defined thresholds are exceeded.

Architecture
EC2 Instance → CloudWatch Metrics → CloudWatch Alarm → SNS → Email Alert

Services Used

AWS EC2

AWS CloudWatch

Amazon SNS

AWS IAM

CloudWatch Agent

What It Monitors

CPU Utilization

Memory Usage

Disk Usage

Instance Health

Alerting

CloudWatch alarms trigger on threshold breaches

Amazon SNS sends real-time email notifications

Security

IAM role attached to EC2 (no access keys used)

Least-privilege IAM policies

Secure SNS topic for alerts

Outcome

Provides real-time visibility into EC2 health with automated alerts, following AWS security best practices.

Resume Line

Built a Cloud Monitoring and Alert System using AWS CloudWatch and SNS to monitor EC2 metrics and send real-time email alerts.

Author

