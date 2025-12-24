# 🛒 Amazon Clone - Fullstack E-commerce

Projet e-commerce professionnel avec architecture en microservices.

## 🏗️ Architecture

Ce projet utilise **Git Submodules** pour séparer le backend et le frontend.

### Repositories
- **Backend :** [amazon-clone-backend](https://github.com/MiL-Dev/e-commerce-backend)
- **Frontend :** [amazon-clone-frontend](https://github.com/MiL-Dev/e-commerce-frontend)

## 📦 Installation

### Cloner le projet avec les submodules
```bash
git clone --recurse-submodules https://github.com/TON-USERNAME/amazon-clone.git
cd amazon-clone
```

### Installer les dépendances

**Backend :**
```bash
cd backend
npm install
npx prisma generate
npx prisma db push
npm run dev
```

**Frontend :**
```bash
cd frontend
npm install
npm run dev
```

## 🔄 Mettre à jour les submodules
```bash
git submodule update --remote
```

## 🛠️ Stack Technique

### Backend
- Node.js + Express + TypeScript
- PostgreSQL + Prisma ORM
- JWT + Bcrypt

### Frontend
- React + TypeScript
- Tailwind CSS

## 👤 Auteur Bounaceur Mohamed

Projet Personnel - Architecture professionnelle