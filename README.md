# Hi, I'm Caio Martins <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px" alt="Waving hand">

## Fullstack Developer · React Native · Python · AWS Serverless
 
I build end-to-end systems — from mobile interfaces to serverless backends and cloud infrastructure.
 
My work lives at the intersection of **mobile development**, **event-driven architecture**, and **AWS cloud services**.
I care deeply about system design, code maintainability, and making technical decisions that scale.
 
Evolving toward backend architecture, distributed systems, and cloud infrastructure.
 
---
 
## 🛠️ Tech Stack
 
**Mobile & Frontend**
 
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
 
**Backend & Cloud**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![AWS Lambda](https://img.shields.io/badge/AWS_Lambda-FF9900?style=flat&logo=awslambda&logoColor=white)
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=flat&logo=amazonapigateway&logoColor=white)
![AppSync](https://img.shields.io/badge/AppSync-E10098?style=flat&logo=amazonaws&logoColor=white)
![EventBridge](https://img.shields.io/badge/EventBridge-FF9900?style=flat&logo=amazonaws&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat&logo=amazondynamodb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
 
**Infrastructure & Tooling**
 
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
 
---
 
## 🔨 Projects
 
### 📍 Geofencing & IoT Trigger System
> Event-driven location system built on AWS
 
A serverless, event-driven system that tracks user location in real time and triggers
automated actions based on geofence boundary events (ENTER / EXIT).
 
**How it works:**
- Mobile app (React Native) sends user position via REST API every 100m or every minute — including background mode
- **AWS Location Service** evaluates whether the user is inside or outside a defined geofence
- **EventBridge** receives the boundary event and routes it to independent Lambda consumers
- Each consumer handles a separate concern: IoT scene execution, push notifications, and event logging
- Loosely coupled architecture — new consumers can be added without modifying existing services
- Infrastructure fully provisioned with **Terraform**
**Why EventBridge?**
Direct Lambda-to-Lambda calls would tightly couple the location processor to every downstream service.
EventBridge decouples producers from consumers, making the system easier to extend and maintain independently.
 
`React Native` `Python` `AWS Lambda` `EventBridge` `AWS Location Service` `DynamoDB` `MySQL` `Terraform`
 
---
 
## 📬 Let's Connect
 
- 💼 [LinkedIn](https://www.linkedin.com/in/caio-martins-30962b142/)
- 📧 caiocalhaum@gmail.com

