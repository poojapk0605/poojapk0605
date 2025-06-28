<!-- GitHub Profile Views -->
<p align="right">
  <img src="https://komarev.com/ghpvc/?username=poojapk0605&label=Profile%20Views&color=0e75b6&style=flat" alt="poojapk0605" />
</p>

# 👋 Hi, I'm Pooja Kannan

🎓 Master’s in Cyber-Physical Systems @ Northeastern University  
🔧 DevOps & MLOps Engineer | Kubernetes • Terraform • GCP & AWS • CI/CD • Monitoring

I’m a DevOps and MLOps engineer with hands-on experience deploying scalable, cloud-native systems using Kubernetes, Terraform, and CI/CD tools across AWS and GCP.

I’ve built end-to-end pipelines, managed infrastructure-as-code, and integrated observability stacks using Prometheus and Grafana. My recent projects include:
- 📦 Deploying an LLM-based chatbot using **GKE**, **Airflow**, and **Pinecone**
- 🛡 Developing a CVE-tracking microservice in **Go** using **Kafka** and **PostgreSQL**

I'm passionate about automation, clean architecture, and building resilient systems.

---

## ⚙️ Tools & Tech I Work With

[![Terraform](https://img.shields.io/badge/IaC-Terraform-blue?logo=terraform)](https://www.terraform.io)
[![GCP](https://img.shields.io/badge/Cloud-GCP-orange?logo=googlecloud)](https://cloud.google.com)
[![AWS](https://img.shields.io/badge/Cloud-AWS-yellow?logo=amazonaws)](https://aws.amazon.com)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-green?logo=githubactions)](https://github.com/features/actions)
[![Kubernetes](https://img.shields.io/badge/Orchestration-Kubernetes-blue?logo=kubernetes)](https://kubernetes.io)
[![Linux](https://img.shields.io/badge/System-Linux-black?logo=linux)](https://www.kernel.org)
[![Python](https://img.shields.io/badge/Scripting-Python-yellow?logo=python)](https://www.python.org)
[![Docker](https://img.shields.io/badge/Container-Docker-blue?logo=docker)](https://www.docker.com)
[![Jenkins](https://img.shields.io/badge/Automation-Jenkins-red?logo=jenkins)](https://www.jenkins.io)
[![Airflow](https://img.shields.io/badge/Workflow-Airflow-3aa0cf?logo=apacheairflow)](https://airflow.apache.org)
[![Grafana](https://img.shields.io/badge/Monitoring-Grafana-f46800?logo=grafana)](https://grafana.com)
[![Prometheus](https://img.shields.io/badge/Monitoring-Prometheus-e6522c?logo=prometheus)](https://prometheus.io)

---

## 📌 Featured Projects

# 🚗 CarPoolEasy – JavaFX Carpooling App with GCP Deployment

CarPoolEasy is a full-stack desktop carpool management application built using JavaFX and MySQL. It allows users to register, login, post rides, and search for available carpool options. The application is designed with clean object-oriented principles and deployed on Google Cloud using Compute Engine and Cloud SQL.

---

## 🧰 Tech Stack

- **Language & UI**: Java, JavaFX, SceneBuilder
- **Backend**: MySQL (Cloud SQL)
- **Cloud**: Google Cloud Platform (Compute Engine, Cloud SQL)
- **Email Notifications**: SMTP
- **Deployment**: GCP startup scripts, secure VM provisioning

---

## 🛠️ Key Features

- 🧾 User Registration & Authentication with hashed passwords  
- 🚗 Create, View, and Search for Ride Posts  
- ✉️ Email verification via SMTP integration  
- 🖥 GUI developed using JavaFX & SceneBuilder  
- ☁️ Deployed on GCP using VM startup script and MySQL Cloud SQL

---

## ⚙️ Deployment Overview

- MySQL Cloud SQL provisioned for data storage  
- GCP VM instance created with startup script to auto-run backend on boot  
- Users interact through a desktop GUI interface built with SceneBuilder  
- Emails triggered via SMTP server integration

---

## 📸 Screenshots  
*(Optional: Add images of your GUI here)*

---

## 🔗 Links

- 📂 GitHub Repo: [CarPoolEasy](https://github.com/poojapk0605/CarPoolEasy)  
- 📫 [Connect on LinkedIn](https://www.linkedin.com/in/poojakannanpk/)

---

## 📄 License  
MIT License



# ☁️ CloudCraft – Full-Stack Node.js App with GCP & Terraform

CloudCraft is a backend application built from scratch using Node.js and deployed on Google Cloud Platform. It provisions cloud infrastructure using Terraform and implements secure CI/CD pipelines with auto-scaling VM deployment, startup scripts, and load balancing.

---

## 🧰 Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MySQL (Cloud SQL)
- **Infrastructure:** Terraform, Packer, Google Cloud Platform
- **CI/CD:** GitHub Actions
- **Security & Auth:** bcrypt, JWT
- **Testing:** Jest
- **Messaging:** Pub/Sub for email verification

---

## 🛠️ Key Features

- 🔐 Role-based user authentication with hashed passwords (bcrypt)  
- 📧 GCP Pub/Sub integration for email verification  
- 🧱 Terraform + Packer for full GCP VM provisioning  
- 🚀 Startup scripts to automate application boot on VM launch  
- 📦 CI/CD with GitHub Actions to rebuild and redeploy new VM templates on push  
- ⚖️ Load balancing and autoscaling using instance templates  
- 🛡️ Secured infrastructure with IAM and GCP firewall rules

---

## ⚙️ Deployment Overview

- Terraform creates VPC, subnets, VM instance, Cloud SQL, Pub/Sub topics  
- Packer builds VM images that run the backend on startup  
- GitHub Actions triggers redeployment upon commit  
- Startup script installs dependencies and launches the Node app on instance boot  
- Cloud SQL manages persistent MySQL data storage

---

## 🖼️ Architecture Diagram  
*(Optional: add a simple diagram here)*

---

## 🔗 Links

- 📂 GitHub Repo: [Cloud_Craft](https://github.com/poojapk0605/Cloud_Craft)  
- 🔗 [LinkedIn Project](https://www.linkedin.com/in/poojakannanpk/)

---

## 📄 License  
MIT License

# 🧠 AskNEU – GCP-Deployed RAG Chatbot with Kubernetes & Airflow

AskNEU is a Retrieval-Augmented Generation (RAG) chatbot designed to answer questions using structured content scraped from Northeastern University websites. The project includes a fully automated data pipeline using Apache Airflow, embedding generation, vector storage with Pinecone, and deployment on GKE with Istio, GitHub Actions, and full-stack observability.

---

## 🧰 Tech Stack

- **Language:** Python, Bash
- **Orchestration:** Apache Airflow
- **Scraping:** Selenium
- **Vector DB:** Pinecone
- **Cloud:** GCP (GKE, GCS, DNS, Cloud NAT)
- **CI/CD:** GitHub Actions
- **Security:** Istio, Cert-Manager
- **Monitoring:** Prometheus, Grafana

---

## 🛠️ Key Features

- 🔄 Automated web scraping using Selenium
- 🧠 Embedding generation and semantic search with Pinecone
- ⚙️ DAG orchestration using Apache Airflow
- ☁️ Containerized deployment on GKE via GitHub Actions
- 🛡️ Secured ingress with Istio and TLS using Cert-Manager
- 📊 Real-time observability using Prometheus + Grafana

---

## ⚙️ Deployment Overview

1. **Data Pipeline:**
   - Airflow DAG scrapes content → stores raw HTML/text in GCS
   - DAG triggers embedding script → stores vectors in Pinecone

2. **Backend Deployment:**
   - Docker containers built and pushed via GitHub Actions
   - Deployed to GKE with Kubernetes manifests and Helm
   - Istio handles routing and TLS termination

3. **Monitoring:**
   - Metrics exported to Prometheus
   - Dashboards visualized in Grafana

---

## 📊 Diagram (Optional)
*(Consider adding an architecture.png here)*

---

## 📦 Folder Structure

AskNEU/
├── airflow/
│ ├── dags/
│ ├── config/
├── deployment/
│ ├── Dockerfile
│ ├── k8s/
├── scraper/
├── embeddings/
├── README.md


---

## 🔗 Links

- 📂 GitHub Repo: [AskNEU](https://github.com/poojapk0605/AskNEU)  
- 🔗 [LinkedIn Profile](https://www.linkedin.com/in/poojakannanpk/)

---

## 📄 License  
MIT License


## 🗂️ Other Noteworthy Projects

Here are a few more hands-on projects I’ve built. You can find the complete list on my GitHub:

- 🔸 [CloudCraft](https://github.com/orgs/cloud-craft-project-fullstack/repositories) – Cloud-native fullstack app with GCP VM's & Terraform  
- 🔸 [MachineLearning-Timeseries](https://github.com/poojapk0605/MachineLearning-Timeseries) – Time series analysis using ARIMA & LSTM  
- 🔸 [CarPoolEasy](https://github.com/poojapk0605/CarPoolEasy) – Carpool coordination app with route and request tracking  
- 🔸 [Miniproject_IOT](https://github.com/poojapk0605/Miniproject_IOT) – Raspberry Pi 4 + sensor data collection  
- 🔸 [Iot-WildGuard-System](https://github.com/poojapk0605/Iot-WildGuard-System) – IoT system to detect wild animal movements via edge sensors  

👉 **Explore more** at [github.com/poojapk0605](https://github.com/poojapk0605)

---

## 📫 Connect With Me

- 🌐 Portfolio: [poojapk0605.github.io](https://poojapk0605.github.io/)
- 💼 LinkedIn: [linkedin.com/in/poojakannanpk](https://www.linkedin.com/in/poojakannanpk/)
- 🧵 Bluesky: [pooja-kannan.bsky.social](https://bsky.app/profile/pooja-kannan.bsky.social)
- 📬 Email: poojahusky@gmail.com

---

## 🔍 I'm actively seeking full-time opportunities in:  
**DevOps · Site Reliability Engineering (SRE) · Cloud Engineering · MLOps**

🌍 Active member of the [MLOps Community](https://mlops.community/)  
🌐 Exploring decentralized platforms via Bluesky  

🛠️ **Let’s automate everything — from infrastructure to ML workflows.**

---

⭐️ Thanks for visiting my profile! Feel free to check out my projects or reach out for collaboration.
