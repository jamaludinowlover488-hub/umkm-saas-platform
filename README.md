# 🏪 UMKM SaaS Platform

**Sistem Informasi Manajemen UMKM** - Platform SaaS all-in-one untuk UMKM Indonesia dengan fitur inventory, POS, customers, payment gateway, dan reporting.

## ✨ Features

### Phase 1: Security & Infrastructure ✅
- ✅ User Authentication & Authorization
- ✅ Role-Based Access Control (RBAC)
- ✅ Secure API Architecture
- ✅ Database with PostgreSQL
- ✅ JWT Token Management

### Phase 2: Core Business (In Progress)
- 🔄 Inventory Management System
- 🔄 Point of Sale (POS)
- 🔄 Customer Management
- 🔄 Financial Reports
- 🔄 Refund & Return System

### Phase 3: Integrations (Planned)
- ⏳ Midtrans Payment Gateway
- ⏳ Fonnte WhatsApp Integration
- ⏳ Email Notifications
- ⏳ PDF/Excel Export
- ⏳ Push Notifications

### Phase 4: Polish (Planned)
- ⏳ Tax Compliance (e-Faktur)
- ⏳ Barcode/QR Scanner
- ⏳ Onboarding Wizard
- ⏳ Error Handling & UX Polish
- ⏳ Performance Optimization

---

## 🛠️ Technology Stack

### Backend
- **Node.js** 18+ with Express.js
- **TypeScript** for type safety
- **PostgreSQL** for database
- **Sequelize/TypeORM** for ORM
- **JWT** for authentication

### Frontend
- **Vue 3** with Composition API
- **Axios** for HTTP client
- **Pinia** for state management
- **Chart.js** for analytics

### Infrastructure
- **Docker** for containerization
- **GitHub Actions** for CI/CD
- **Railway/Render** for hosting
- **AWS S3** for file storage

---

## 🚀 Quick Start

### Prerequisites
- Node.js 18+
- PostgreSQL 13+
- Docker & Docker Compose
- Git

### Backend Setup

```bash
# Clone repository
git clone https://github.com/jamaludinowlover488-hub/umkm-saas-platform.git
cd umkm-saas-platform

# Setup environment
cp .env.example .env
# Edit .env with your actual credentials

# Install dependencies
npm install

# Start PostgreSQL with Docker
docker-compose up -d

# Run migrations
npm run migrate

# Seed database (optional)
npm run seed

# Start backend server
npm run dev

# Go to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
