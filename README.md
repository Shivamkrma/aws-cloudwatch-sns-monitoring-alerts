Overview

This project demonstrates a real-time cloud monitoring and alerting system built using AWS CloudWatch and Amazon SNS. It continuously monitors EC2 instance performance and automatically sends email alerts when predefined thresholds are crossed.

Architecture

EC2 Instance → CloudWatch Metrics → CloudWatch Alarm → SNS → Email Notification

Services Used

AWS EC2

AWS CloudWatch

Amazon SNS

AWS IAM

CloudWatch Agent

Monitoring Scope

CPU Utilization

Memory Usage

Disk Usage

EC2 Instance Health

Alerting Mechanism

CloudWatch alarms evaluate metrics in real time

Amazon SNS delivers instant email notifications on threshold breaches

Security Implementation

IAM role-based access (no hardcoded AWS credentials)

Least-privilege IAM policies

Secure SNS topic configuration

Outcome

Delivers continuous visibility into EC2 health with automated alerts, following AWS security and operational best practices.
