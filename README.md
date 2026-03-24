# 🏢 ERP Platform — Enterprise Resource Planning System

<div align="center">

![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white)
![ASP.NET](https://img.shields.io/badge/ASP.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Angular](https://img.shields.io/badge/Angular_17-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![Microservices](https://img.shields.io/badge/Architecture-Microservices-orange?style=for-the-badge)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

**Academic Project — Polytech Tunis**

Developed by **Wassef BEN RGAYA**

</div>

---

## 📖 Overview

A full-stack **Enterprise Resource Planning (ERP) Platform** built with C# ASP.NET Core microservices backend and an Angular 17 frontend. The system provides a complete business management solution with a clean layered architecture and modern web interface.

---

## 🗂️ Project Repositories

| Repository | Stack | Description |
|------------|-------|-------------|
| 🔧 [erp-backend](https://github.com/Wassef-Ben-Rgaya/erp-backend) | C# · ASP.NET Core · SQL Server | Microservices REST API — API / Core / DAL / Service |
| 📱 [erp-frontend](https://github.com/Wassef-Ben-Rgaya/erp-frontend) | Angular 17 · TypeScript · HTML/CSS | Web client — components, services, SSR |

---

## 🏗️ System Architecture

```
┌────────────────────────────────────────────┐
│              erp-frontend                   │
│           Angular 17 Web App                │
│   Components · Services · HTTP Client       │
└───────────────────┬────────────────────────┘
                    │ REST API (HTTP)
                    ▼
┌────────────────────────────────────────────┐
│               erp-backend                   │
│         ASP.NET Core Microservices          │
│                                             │
│  ┌─────────┐  ┌─────────┐  ┌───────────┐  │
│  │   API   │  │ Service │  │    DAL    │  │
│  │ Layer   │  │  Layer  │  │   Layer   │  │
│  └─────────┘  └─────────┘  └─────┬─────┘  │
│                                   │        │
│              Core / Models        │        │
└───────────────────────────────────┼────────┘
                                    │
                               SQL Server
```

---

## ✨ Key Features

### 🔧 Backend (Microservices)
- Clean layered architecture: API → Service → DAL → Core
- RESTful API endpoints
- Entity Framework Core with SQL Server
- Modular microservices design

### 📱 Frontend (Angular 17)
- Modern responsive web interface
- Angular HttpClient for API communication
- Server-Side Rendering (SSR) support
- TypeScript strict mode

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Backend language | C# |
| Backend framework | ASP.NET Core |
| Backend architecture | Microservices · Layered |
| Database | SQL Server |
| ORM | Entity Framework Core |
| Frontend framework | Angular 17 |
| Frontend language | TypeScript |
| Frontend styling | HTML5 · CSS3 |

---

## 🚀 Quick Start

```bash
# Backend
git clone https://github.com/Wassef-Ben-Rgaya/erp-backend.git

# Frontend
git clone https://github.com/Wassef-Ben-Rgaya/erp-frontend.git
```

Refer to each repository's `README.md` for specific setup instructions.

---

## 👨‍💻 Author

**Wassef BEN RGAYA**
Computer Engineering — AI & Data Science Specialization

📍 Nabeul, Tunisia
📧 wassefbenrgaya24@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/wassef-ben-rgaya-600817188)
🐙 [GitHub](https://github.com/Wassef-Ben-Rgaya)

---

## 📄 License

This project was developed as part of an academic project at Polytech Tunis.
© 2025 Wassef BEN RGAYA — All rights reserved.
