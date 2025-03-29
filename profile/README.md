# 🛍️ MeraStore - E-commerce Fulfillment Platform

Welcome to **MeraStore** – a **scalable, microservices-driven e-commerce fulfillment platform** designed to handle orders, inventory, payments, and logistics efficiently. 🚀

> ⚠️ **Self-Learning Project**  
> This project is a personal learning initiative to experiment with **microservices, event-driven architecture, and cloud-native solutions**. It is **not** intended for production use.

---

## 📌 Features

✅ **User Management** – Authentication & authorization 🔐  
✅ **Product Management** – Listings, categories & product details 📦  
✅ **Inventory Tracking** – Real-time stock updates 🏷️  
✅ **Order Processing** – Seamless order placement & tracking 📑  
✅ **Shopping Cart** – Multi-item cart management 🛒  
✅ **Secure Payments** – Gateway integration for transactions 💳  
✅ **Shipping & Logistics** – Efficient fulfillment & delivery 🚛  
✅ **Advanced Search** – Elasticsearch-powered product discovery 🔍  
✅ **Analytics & Insights** – Sales reports & trends 📊  
✅ **Notifications** – Email, SMS, and push alerts 📢  

---

## 🏗️ Tech Stack

| **Category**      | **Technology** |
|------------------|---------------|
| **Backend**      | ![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white) ![ASP.NET](https://img.shields.io/badge/ASP.NET-5C2D91?style=for-the-badge&logo=dotnet&logoColor=white) |
| **Frontend**     | ![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) (Not In plan currently) |
| **Database**     | ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white) |
| **Caching**      | ![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white) |
| **Messaging**    | ![Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=for-the-badge&logo=apache-kafka&logoColor=white) |
| **Search**       | ![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white) |
| **Logging**      | ![Kibana](https://img.shields.io/badge/Kibana-005571?style=for-the-badge&logo=kibana&logoColor=white) |
| **Containerization** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) |
| **Orchestration** | ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white) |
| **CI/CD**        | ![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white) ![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=for-the-badge&logo=azure-devops&logoColor=white) |
| **API Gateway**    | ![Ocelot](https://img.shields.io/badge/Ocelot-008AD7?style=for-the-badge) ![NGINX](https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white) |
| **Monitoring & Observability** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) ![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=for-the-badge&logo=opentelemetry&logoColor=white) |
| **Event-Driven Architecture** | ![EventStore](https://img.shields.io/badge/EventStore-3E3E3E?style=for-the-badge) ![CQRS](https://img.shields.io/badge/CQRS-DD0031?style=for-the-badge) |
| **Authentication** | ![OAuth2](https://img.shields.io/badge/OAuth2-3C3C3C?style=for-the-badge&logo=oauth&logoColor=white) |
| **Testing**        | ![xUnit](https://img.shields.io/badge/xUnit-5C2D91?style=for-the-badge&logo=xunit&logoColor=white) ![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) |
| **Infrastructure as Code** | ![Terraform](https://img.shields.io/badge/Terraform-623CE4?style=for-the-badge&logo=terraform&logoColor=white) ![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white) |

---

## 🏗️ Microservices

| **Service** | **Functionality** |
|------------|------------------|
| **User Service** 👤 | Manages authentication, authorization & profiles. |
| **Product Service** 🛒 | Handles product listings, categories & attributes. |
| **Inventory Service** 📦 | Tracks stock levels & warehouse operations. |
| **Order Service** 📑 | Processes customer orders & transactions. |
| **Cart Service** 🛍️ | Manages shopping carts & wishlists. |
| **Payment Service** 💳 | Handles transactions & payment gateways. |
| **Shipping Service** 🚛 | Manages shipping, tracking & delivery. |
| **Auth Service** 🔑 | Secure authentication (OAuth2, JWT). |
| **Notification Service** 📢 | Sends email, SMS & push notifications. |
| **Search Service** 🔎 | Elasticsearch-powered product search. |
| **Review Service** ⭐ | Handles customer reviews & ratings. |
| **Warehouse Service** 📊 | Manages warehouse logistics & stock movements. |
| **Analytics Service** 📈 | Generates sales & operational insights. |
| **Discount Service** 🎟️ | Handles coupons, vouchers & promotions. |
| **API Gateway** 🚦 | Centralized entry point for all microservices. |
| **Fraud Detection Service** 🛑 | Detects and prevents fraudulent transactions. |

---

## 🛠️ Shared Libraries & Infrastructure

### 📦 **Shared Libraries**
- **Shared Kernel** 🏗️ – Common utilities, models & event handling.
- **API Gateway** 🌍 – Centralized API management.
- **Auth Library** 🔐 – Authentication & authorization logic.
- **Logging Library** 📜 – Structured logging for Kibana.
- **Rate-Limiting Library** ⏳ – Prevents API abuse.

### 🏗️ **Infrastructure**
- **Infra-Config** 🏢 – Infrastructure as code (IaC) setup.
- **Docker Images** 🐳 – Containerized microservices.
- **CI/CD Pipelines** ⚡ – Automated deployments (GitHub Actions, ArgoCD).

---

## 🚀 Getting Started

### ✅ Prerequisites
Ensure you have the following installed before running the project:
- **Docker** 🐳 – For containerization.
- **Kubernetes** 🚢 – For orchestration.
- **Node.js** 🟢 – For frontend development.
- **.NET 9** 🏗️ – For backend services.
- **PostgreSQL & Sql Server** 🛢️ – Database.

### 🛠️ Setup

1️⃣ **Clone the repository**  

1. Download the script by right-clicking the link below and selecting **"Save link as..."**:

   [Download setup-mera-store.ps1](https://gist.githubusercontent.com/sanjyotagureddy/0e06941f674d00ef483505083c6544ba/raw)

2. Execute the downloaded script in PowerShell or CMD.
