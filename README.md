<div align="center">
  <img src="./banner.svg" width="100%" alt="Himanshu Shukla — Cloud & AI Automation Engineer"/>
</div>

<br/>

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-ronaldweasly-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ronaldweasly)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-himanshuxshukla-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/himanshuxshukla)
[![Email](https://img.shields.io/badge/Email-the.himanshushukla0%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:the.himanshushukla0@gmail.com)
[![Location](https://img.shields.io/badge/Location-Jaipur%2C%20Rajasthan-00d4ff?style=flat-square&logo=googlemaps&logoColor=white)](#)

</div>

---

## 🛠️ Tech Stack

<div align="center">

**☁ Cloud & DevOps**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![EC2](https://img.shields.io/badge/EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white)
![ECS](https://img.shields.io/badge/ECS_Fargate-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/S3-569A31?style=flat-square&logo=amazons3&logoColor=white)
![RDS](https://img.shields.io/badge/RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![CloudWatch](https://img.shields.io/badge/CloudWatch-FF4F8B?style=flat-square&logo=amazoncloudwatch&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)

**⚡ Backend & Databases**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**🧠 AI & Automation**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6B4EFF?style=flat-square&logoColor=white)
![LangChain](https://img.shields.io/badge/Jina_AI-000000?style=flat-square&logoColor=white)
![SearXNG](https://img.shields.io/badge/SearXNG-EF5552?style=flat-square&logoColor=white)

**🔧 CI/CD & Monitoring**

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

</div>

---

## 🔥 Featured Projects

### 🚀 [CloudHarvest — Autonomous Lead Intelligence Platform](https://github.com/ronaldweasly)

> **$2 per 1,000 qualified leads · 7 production campaigns · €12,000 client revenue**

```
AWS Architecture:  VPC → ALB → SQS → ECS Workers → RDS PostgreSQL → Google Sheets
AI Layer:          Lambda → Ollama (LLM scoring) → ICP matching → n8n webhook
Scale:             0 → 20 ECS workers in under 2 min · 500+ domains/run
```

- Terraform-provisioned VPC with ALB, private worker subnets, SQS job queues
- SQS queue depth drives ECS autoscaling — fully self-monitoring via CloudWatch + SNS
- Lambda invokes Ollama on dedicated EC2 to score each lead against ICP criteria
- 50GB+ S3 data lake with Glacier lifecycle archiving · cut cold-start time 60%

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![ECS](https://img.shields.io/badge/ECS-FF9900?style=flat-square&logo=amazonecs&logoColor=white)
![SQS](https://img.shields.io/badge/SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

---

### 🤖 Autonomous AI Agency — Multi-Agent Workflow System

> **2 hours manual deploy → 11 minutes automated · 3× weekly ship velocity**

```
Pipeline:  GitHub Push → CodeBuild (test + SonarQube gate) → ECR → CloudFormation → ECS rolling deploy
Envs:      dev / staging / prod · fully AWS-native · zero manual steps
```

- Multi-agent system: lead discovery → code generation → QA → deployment
- LLM orchestration with isolated sandbox execution
- Serverless CI/CD with multi-environment promotion across dev/staging/prod

![CodePipeline](https://img.shields.io/badge/CodePipeline-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![CodeBuild](https://img.shields.io/badge/CodeBuild-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![ECR](https://img.shields.io/badge/ECR-FF9900?style=flat-square&logo=amazonaws&logoColor=white)
![CloudFormation](https://img.shields.io/badge/CloudFormation-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=flat-square&logo=sonarqube&logoColor=white)

---

### 🧠 Railway Monitoring System — ML Fault Detection

> **50+ daily diagnostic reports automated · manual review: 3h → 20 min**

- Microservices-based ML platform for real-time fault detection & prediction
- Live monitoring dashboard with alerting (Grafana + Prometheus)
- Data flows mapped across large-scale on-premises monitoring stack

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)

---

### 🎲 Board Game Web App — Full-Stack AWS Deployment

- Spring Boot + role-based authentication (Spring Security)
- Full CRUD · MVC architecture · AWS VPS deployment
- Reverse proxy routing (Nginx) + live monitoring (Grafana + Prometheus)

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=ronaldweasly&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0a0e1a&title_color=00d4ff&icon_color=4a9eff&text_color=94a3b8&ring_color=8b5cf6" alt="GitHub Stats"/>

<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ronaldweasly&layout=compact&theme=tokyonight&hide_border=true&bg_color=0a0e1a&title_color=00d4ff&text_color=94a3b8" alt="Top Languages"/>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=ronaldweasly&theme=tokyonight&hide_border=true&background=0a0e1a&stroke=00d4ff&ring=8b5cf6&fire=ff4757&currStreakLabel=00d4ff" alt="GitHub Streak"/>

</div>

---

## 🎯 Current Focus

```yaml
goals:
  - DevOps & cloud engineering (production-first)
  - System design & scalability
  - AWS Solutions Architect certification path
  - Building open-source cloud tooling
```

---

## 🏆 Certifications

| Certification | Issuer |
|---|---|
| 🔴 Red Hat Certified System Administrator (RHCSA) | Red Hat Inc. |
| 🍃 MongoDB Developer / Administrator | MongoDB University |
| 🚂 Infrastructure Internship | Indian Railways — BLW Varanasi, 2024 |

---

<div align="center">

**📫 Let's connect**

[![GitHub](https://img.shields.io/badge/github.com%2Fronaldweasly-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ronaldweasly)
[![LinkedIn](https://img.shields.io/badge/linkedin.com%2Fin%2Fhimanshuxshukla-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/himanshuxshukla)

<br/>

*⭐ Consistency > Motivation*

</div>
