# Ma'ed SaaS: High-Performance Multi-Tenant Enterprise Ecosystem

[![Stack](https://img.shields.io/badge/Stack-Django%20%7C%20Next.js%20%7C%20PostgreSQL-blue)](https://github.com/Getabil2/maed-saas-showcase)
[![Status](https://img.shields.io/badge/Status-Production--Ready-success)](https://github.com/Getabil2/maed-saas-showcase)

**Ma'ed SaaS** is a high-end, multi-tenant enterprise platform designed to bridge the gap between sophisticated SaaS architecture and local community needs. Built with a focus on **Monetization**, **Transparency**, and **Localization**, this project showcases my ability to architect and implement complex, scalable systems.

---

## 🚀 Key Architectural Highlights

### 🛡️ 1. Isolated Multi-Tenancy (Schema-Level)
- **Architecture**: Implemented a shared-database, separate-schema architecture using `django-tenants`.
- **Security**: Ensures strict data isolation between tenants (e.g., Hotels, Pharmacies, Communities) while sharing the same application logic.
- **Scalability**: Capable of handling hundreds of isolated tenants with minimal overhead.

### 💰 2. Advanced Monetization Engine
- **Feature Gating**: Granular control over platform capabilities (AI Support, ERP Modules, CRM).
- **Localized Logic**: Implemented a **3-day grace period** specifically for the Ethiopian market to account for bank transfer delays, ensuring a premium user experience without service interruption.
- **Dynamic Pricing**: Support for monthly, yearly, and lifetime subscriptions with automatic access management.

### 🤝 3. Community Trust Engine (Transparency Ledger)
- **Accountability**: Designed for "Edirs" and local communities to manage funds transparently.
- **Public Audit**: Generates secure, read-only audit links for community members.
- **Privacy Compliance**: Strictly filters transaction data to show amounts and purposes while masking personal identities, aligning with modern privacy standards.

### 🌍 4. Military-Grade Localization
- **Ethiopian Languages**: Full support for **Amharic (አማርኛ)**, **Oromo (Afaan Oromoo)**, and **Tigrinya (ትግርኛ)**.
- **Dynamic Injection**: Custom middleware to inject Ethiopian language metadata into the Django registry, solving common "unknown language code" errors in enterprise frameworks.

---

## 🛠️ Technical Stack

### Backend (Python/Django)
- **Framework**: Django REST Framework (DRF).
- **Database**: PostgreSQL (Multi-schema).
- **Cache/Broker**: Redis.
- **Security**: JWT Authentication, Sentry Integration, Security Hardening Headers.
- **Documentation**: Automated OpenAPI 3.0 specs with `drf-spectacular`.

### Frontend (TypeScript/Next.js)
- **Framework**: Next.js 16 (App Router).
- **Styling**: Tailwind CSS with Framer Motion for high-end micro-animations.
- **Visualization**: Recharts for real-time revenue and tenant health metrics.
- **UI/UX**: Custom dark-mode aesthetic with Glassmorphism effects.

---

## 📊 Developer Skill Showcase

- **Full-Stack Orchestration**: Bridging complex DRF APIs with high-performance Next.js interfaces.
- **DevOps**: Docker-composed environment with automated migrations and dependency management.
- **API Design**: Clean, RESTful architectures with robust permission layers (Owner, Admin, Staff, Customer).
- **Problem Solving**: Implementing "Self-Healing" middleware and registries to handle configuration drift.

---

---

## 🔗 Connect with Me

- **Professional CV**: [Getabil Mengistu CV](file:///home/g888/Desktop/my-SAAS/mycv/Getabil_Mengistu_CV.md)
- **GitHub**: [Getabil2](https://github.com/Getabil2)
- **LinkedIn**: [Getabil Mengistu](https://www.linkedin.com/in/getabil-mengistu-738b5523a/)
- **Portfolio Project**: [Ma'ed SaaS Showcase](https://github.com/Getabil2/maed-saas-showcase)

---

> [!NOTE]
> This repository is a **showcase of architecture and concepts**. The core proprietary logic is maintained in a private repository to protect enterprise intellectual property.

