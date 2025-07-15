# CloudWatch + SNS Alerting System

This project sets up monitoring for EC2 instances and sends notifications using Amazon SNS.

## ✅ AWS Services Used
- Amazon CloudWatch
- Amazon SNS
- EC2

## 📊 Features
- Monitor CPU utilization of EC2 instances
- Send email alerts if CPU > threshold
- Create CloudWatch Alarm and SNS topic

## 🛠 Setup Instructions
1. Create an SNS topic and subscribe with your email
2. Create a CloudWatch alarm for CPUUtilization
3. Link the alarm action to the SNS topic

## 💡 Use Cases
- Proactive alerting for performance issues
- Notifications on EC2 failures or threshold breaches
