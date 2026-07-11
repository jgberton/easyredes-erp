<p align="center">
  <img src="./assets/banner.png" width="100%">
</p>

<p align="center">

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000000?style=for-the-badge&logo=expo&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Cloud Functions](https://img.shields.io/badge/Cloud_Functions-FF9800?style=for-the-badge&logo=firebase&logoColor=white)

</p>

# 🛡 EasyRedes ERP

### Operational ERP built for safety net installation companies.

EasyRedes is a cross-platform ERP that centralizes the entire operational workflow of field service companies, from customer management and quotations to inventory control, scheduling, PDF generation and service execution.

Designed to replace spreadsheets and manual processes with a modern, cloud-native platform.

> **From quotation to installation. Everything connected.**

---

# 🎯 Business Problem

Small and medium-sized safety net installation companies commonly manage operations using spreadsheets, handwritten notes and disconnected tools.

This creates problems such as:

- Inventory inaccuracies
- Manual quotation errors
- Poor customer history
- Difficult scheduling
- No operational visibility
- Time wasted on repetitive tasks

EasyRedes was designed to digitize the complete workflow through a single platform.

---

# 👨‍💻 My Role

I designed and developed the product from concept to a functional beta with a production-oriented architecture.  

As the founder, product lead and full-stack developer, I was responsible for:

- Product Discovery
- UX/UI Design
- Business Rules
- Software Architecture
- Mobile Development
- Web Development
- Firebase Infrastructure
- Authentication
- Firestore Data Modeling
- Cloud Functions
- PDF Generation
- Inventory Logic
- CRM
- Multi-tenant Architecture
- Security Rules
- Mercado Pago Integration
- Deployment

---

# 📱 Screenshots

<p align="center">
  <img src="./assets/prints.png" width="100%">
</p>

---

# ✨ Core Features

| Feature | Description |
|----------|-------------|
| 📅 Scheduling | Visit and quotation management |
| 👥 CRM | Customer registration and history |
| 📦 Inventory | Automatic stock control |
| 📄 PDF Generator | Professional quotations and receipts |
| 🧮 Smart Calculations | Material calculation based on business rules |
| ⚙ Service Execution | Automatic stock debit after completion |
| 🔒 Multi-tenant | Company-isolated data |
| ☁ Cloud Sync | Firebase real-time synchronization |
| 📱 Cross-platform | Responsive Web and Android from a shared React Native codebase |
| 💳 Subscription Foundation | Mercado Pago backend integration prepared for SaaS billing |

---

# 🏗 Architecture

```text
                React Native + Expo Router
                           │
                           ▼
                  Authentication Gate
                           │
                           ▼
             Context Facades and Domain Hooks
                           │
                           ▼
      Repositories + TTL Cache + Focused Listeners
                           │
                           ▼
                     Cloud Firestore
                    /       |        \
                   ▼        ▼         ▼
          Inventory Batch   CRM    Scheduling
              Updates               & Quotes

        Firebase Storage          Cloud Functions
          Logos and PDFs          Mercado Pago Backend
```

---

# 📊 Technical Highlights

- Multi-tenant architecture
- Firebase Security Rules
- Repository Pattern
- Context-based State Management
- Cloud Functions
- Cache-first data loading with TTL
- Firestore Batch Operations
- Real-time synchronization
- PDF generation
- Responsive Web support
- Cross-platform architecture

---

# ⚙ Tech Stack

## Frontend

- React Native
- Expo
- Expo Router
- TypeScript
- NativeWind

## Backend

- Firebase Authentication
- Firestore
- Cloud Functions
- Storage
- Hosting

## Payments

- Mercado Pago

## Infrastructure

- Firebase Hosting
- Security Rules
- Cloud Storage

---

# 🚀 Technical Challenges

## Inventory Synchronization

Building an inventory system capable of automatically updating stock during service execution while keeping Firestore costs low.

---

## Business Rules

Implementing domain-specific calculations for safety net installation, including material estimation, labor costs and quotation generation.

---

## Multi-tenant Architecture

Keeping company data isolated while maintaining a simple Firestore structure.

---

## PDF Generation

Creating professional quotations and receipts directly from the application.

---

## Performance

Optimizing Firestore listeners, local cache and repository architecture to reduce reads and improve responsiveness.

---

# 🧠 Domain Logic

EasyRedes is not a generic CRUD application.

Its quotation engine translates real installation rules into software, including:

- Opening dimensions and perimeter calculations
- Safety-net height ranges
- Rope and hook estimation
- Structure and fixing methods
- Material cost calculation
- Suggested pricing and margin visibility
- Automatic stock debit after service execution

This domain-specific logic connects quotation, execution and inventory in a single operational workflow.  
---

# 📈 Why this project stands out

✅ Complete ERP workflow

✅ Production-oriented architecture

✅ Multi-tenant SaaS

✅ Firebase Security Rules

✅ Automatic inventory management

✅ Professional PDF generation

✅ Cloud-native backend

✅ Cross-platform

✅ Responsive Web

✅ Scalable multi-tenant foundation

---

# 🛠 Engineering Roadmap

EasyRedes is currently a functional beta prepared for closed testing and product validation.

### Implemented

- Complete quotation-to-execution workflow
- Multi-tenant Firestore structure
- Inventory batch updates
- PDF quotations and receipts
- Security Rules
- Mercado Pago backend foundation

### Next Engineering Milestones

- Automated tests for inventory debit
- Secure Mercado Pago webhook validation
- Query limits and pagination
- Subscription checkout interface
- CI/CD pipeline
- App Check and rate limiting
- Refactoring of large operational screens  

# 📚 What I Learned

EasyRedes was my most architecture-focused project.

Unlike consumer applications, building an ERP required translating real operational workflows into software while balancing usability, scalability and maintainability.

This project strengthened my understanding of domain modeling, data architecture, business rules and enterprise software design.

---

# 🔗 Repository Purpose

This repository is a **case study** showcasing the product architecture, business decisions and technical implementation behind EasyRedes.

The production source code remains private.

---

## ⭐ Building software that solves real operational problems.
