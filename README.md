<img width="1920" height="1080" alt="Screenshot (265)" src="https://github.com/user-attachments/assets/84d399bc-d0a5-42e0-9766-e9cd8cf39698" /># Task-2: AWS Cloud Monitoring and Alerts

## 🎯 Objective
Configure cloud monitoring and alerts for a cloud-based application using AWS CloudWatch as part of internship deliverables.

## 🛠️ Services Used
- AWS CloudWatch (Metrics, Dashboards, Alarms)
- AWS S3 (Monitored service)

## 📊 Monitoring Overview
A CloudWatch dashboard was created to visualize S3 API metrics.

- **Monitored Metric:** S3 CreateBucket - CallCount
- **Namespace:** AWS/Usage
- **Statistic:** Average
- **Visualization:** Line graph widget on CloudWatch dashboard

## 🚨 Alerts Overview
A CloudWatch metric alarm was configured to trigger based on threshold conditions.

- **Alarm Type:** Metric Alarm
- **Threshold Condition:**  
CallCount >= 1 for 1 datapoint within 5 minutes
- **Alarm State Transitions:** OK / ALARM / INSUFFICIENT_DATA

## 📁 Screenshots
Screenshots included:
- CloudWatch Dashboard
- Dashboard List
- Alarm List
- Alarm Details

## 📦 Deliverable Summary
✔ Cloud Monitoring Configured  
✔ CloudWatch Dashboard Created  
✔ Alerts Configured via CloudWatch Alarm  
✔ Screenshots Included for Verification  

## 🧠 Learning Outcome
Gained hands-on experience with AWS CloudWatch monitoring, metric dashboards, and alert configurations.


