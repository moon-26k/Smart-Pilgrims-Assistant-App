# 🛕 Smart Pilgrims Assistant App

An AI-powered assistant designed to help pilgrims with real-time information and guidance.

## 🚀 Tech Stack

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)
![Gemini AI](https://img.shields.io/badge/Google%20Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)

---
## ✨ What Smart Pilgrims Assistant Does

The **Smart Pilgrims Assistant App** is an AI-driven platform designed to enhance the pilgrimage experience. It simplifies journey planning, provides real-time assistance , and ensures that pilgrims have all the resources they need at their fingertips.

### 💡 The Core Workflow

* **🗺️ Plan Journey:** Users can search for pilgrimage sites and get detailed itineraries.
* **🤖 AI Guidance:** Integrated **Gemini AI** to answer queries, provide historical context, and offer real-time help.
* **📍 Smart Navigation:** Uses **Geoapify** to find nearby amenities like water stations, medical camps, and resting areas.
* **🔐 Secure Access:** Seamless login using **Google OAuth** and protected user profiles.

---

### 🌟 Key Features

* **🗣️ Multilingual Support:** AI assistance that understands and responds in multiple languages to help pilgrims from diverse backgrounds.
* **🌦️ Real-time Alerts:** Stay updated with weather conditions and local authorities' announcements.
* **📂 Resource Catalog:** A structured service catalog to find transport, accommodation, and emergency contacts.
* **📸 Visual Insights:** A clean, responsive dashboard (Vite + React) for a smooth user experience.


## 📂 Project Structure

```bash
Smart-Pilgrims-Assistant-App/
├── 📁 AI_Core/
│   ├── crowd_engine.py
│   ├── tts_engine.py
│   └── yolov8s.pt
│
├── 📁 Backend/
│   ├── 📁 config/
│   ├── 📁 controllers/
│   ├── 📁 models/
│   ├── 📁 routes/
│   ├── 📁 socket/
│   ├── 📁 utils/
│   ├── .Sampleenv
│   └── index.js
│
├── 📁 Frontend/
│   ├── 📁 public/
│   ├── 📁 src/
│   │   ├── 📁 api/
│   │   ├── 📁 components/
│   │   ├── 📁 pages/
│   │   ├── 📁 temple1/
│   │   └── App.jsx
│   │
│   └── vite.config.js
│
└── README.md
```
## ⚙️ Detailed Setup Guide

### 1. Prerequisites
* **Node.js** (v18+)
* **MySQL** Database (Cloud or Local)
* **API Keys:** Gemini AI, Cloudinary, and Geoapify.

---

### 2. Backend Setup
Go to the backend folder, install dependencies, and configure environment variables.

```bash
cd Backend
npm install

# Admin & DB
ADMIN_EMAIL=your-email@example.com
DATABASE_URL=mysql://username:password@host:port/database_name

# AI & Maps
GEMINI_API_KEY=your_gemini_api_key
GEOAPIFY_API_KEY=your_geoapify_api_key

# Cloudinary & Auth
CLOUDINARY_URL=cloudinary://api_key:api_secret@cloud_name
JWT_SECRET=your_jwt_secret
GOOGLE_CLIENT_ID=your_google_client_id

npm run dev


## 3️. Frontend Setup

Navigate to the frontend folder:

```bash
cd Frontend
npm install
```

Create a `.env` file inside the Frontend folder and add:

```env
VITE_GOOGLE_CLIENT_ID=your_google_client_id
VITE_API_URL=http://localhost:5000
```

Run the frontend:

```bash
npm run dev
```

---

# 🔑 Environment Variables Configuration

| Category | Variables | Description |
|----------|-----------|-------------|
| **Admin** | `ADMIN_EMAIL` | Primary admin email address |
| **Database** | `DATABASE_URL`, `DB_MODE`, `DB_SSL` | MySQL database connection & deployment configuration |
| **Gemini AI** | `GEMINI_API_KEY`, `GEMINI_API_KEY_BACKUP` | API keys generated from Google AI Studio |
| **Authentication** | `JWT_SECRET`, `REFRESH_TOKEN_SECRET`, `GOOGLE_CLIENT_ID` | JWT authentication & Google OAuth setup |
| **Maps & Search** | `GEOAPIFY_API_KEY`, `SERP_API_KEY` | Location-based services and search support |
| **Email (SMTP)** | `SMTP_HOST`, `SMTP_PORT`, `SMTP_USER`, `SMTP_PASS` | SMTP configuration for notifications & emails |

---

# 🤝 Acknowledgements

We sincerely thank the following contributors and technologies that made this project possible:

- **Project Maintainers** — For providing the opportunity to contribute to this impactful initiative.
- **Open Source Community** — For the amazing libraries, frameworks, and developer tools.
- **Google Gemini API** — For powering the AI-driven assistant features.
- **Our Contributors** — Everyone who helped improve and support this project.

---
<div align="center">

<img src="Frontend/src/assets/logo.png" alt="Divya Yatra Logo" width="120" />

# 🕉️ Divya Yatra — Smart Pilgrims Assistant

### *A full-stack AI-powered platform for a safer, smarter & spiritual yatra experience*

[![Made with React](https://img.shields.io/badge/Frontend-React_19-61DAFB?logo=react&logoColor=white)](https://react.dev)
[![Node.js Backend](https://img.shields.io/badge/Backend-Node.js_+_Express-339933?logo=node.js&logoColor=white)](https://nodejs.org)
[![MySQL](https://img.shields.io/badge/Database-MySQL_+_Sequelize-4479A1?logo=mysql&logoColor=white)](https://www.mysql.com)
[![Gemini AI](https://img.shields.io/badge/AI-Google_Gemini-4285F4?logo=google&logoColor=white)](https://ai.google.dev)
[![Socket.IO](https://img.shields.io/badge/Realtime-Socket.IO-010101?logo=socket.io)](https://socket.io)
[![Deployed on Vercel](https://img.shields.io/badge/Deployed-Vercel-black?logo=vercel)](https://divya-yatra-tit.vercel.app)

**Live Demo →** [divyayatra.xyz](https://www.divyayatra.xyz) &nbsp;|&nbsp; [divya-yatra-tit.vercel.app](https://divya-yatra-tit.vercel.app)

</div>

---

## 📋 Table of Contents

- [🌟 Overview](#-overview)
- [✨ Features](#-features)
- [🏗️ Architecture](#️-architecture)
- [🚀 Getting Started](#-getting-started)
  - [Prerequisites](#prerequisites)
  - [Environment Setup](#environment-setup)
  - [Backend Setup](#backend-setup)
  - [Frontend Setup](#frontend-setup)
- [🔑 Environment Variables Reference](#-environment-variables-reference)
- [📡 API Routes Reference](#-api-routes-reference)
- [🛠️ Tech Stack](#️-tech-stack)
- [📁 Project Structure](#-project-structure)
- [🌐 Deployment](#-deployment)
- [🤝 Contributing](#-contributing)

---

## 🌟 Overview

**Divya Yatra** is a comprehensive smart pilgrim management platform designed for Mahakaleshwar Temple, Ujjain — engineered to scale for **100+ million devotees** at Simhastha Kumbh 2028.

The platform addresses critical challenges faced by pilgrims:
- 🚨 Stampede prevention via real-time crowd density monitoring
- 🔍 AI-powered lost & found system
- 👨‍👩‍👧 Family safety tracking with live SOS alerts
- 🎟️ Priority ticketing & time-slot booking
- 🤖 Multilingual AI travel planner (Gemini AI)
- 📺 Live Darshan streaming
- 🅿️ Smart parking marketplace

---

## ✨ Features

| Feature | Description |
|---|---|
| **🎟️ Priority Ticketing** | Time-slot booking with VIP priority & real-time availability |
| **📡 Zone Crowd Monitoring** | Live RFID-based zone density tracking with QR scanner |
| **👨‍👩‍👧 Family Safety Mode** | Real-time GPS family tracking, voice SOS, guardian rescue routes |
| **🧠 AI Crowd Detection** | YOLOv8-powered crowd analysis with live heatmaps |
| **📺 Live Darshan** | HD temple streaming with multiple camera views |
| **🔍 AI Lost & Found** | AI image matching with real-time item registration alerts |
| **🗺️ Interactive Divine Map** | 3D Leaflet map of Ujjain with GPS navigation & crowd overlay |
| **🤖 AI Yatra Planner** | Gemini AI chatbot with multilingual support & custom itineraries |
| **🅿️ Parking Marketplace** | Peer-to-peer parking slot listing, booking & management |
| **🆘 Emergency SOS** | One-tap geo-tagged emergency broadcast to admin |
| **⚙️ Admin Dashboard** | Full control panel: zone management, alerts, analytics, user management |
| **📊 Real-time Socket.IO** | Live data push for crowd metrics, location tracking & alerts |

---

## 🏗️ Architecture

```
Smart-Pilgrims-Assistant-App/
├── Backend/        ← Node.js + Express + Sequelize REST API
└── Frontend/       ← React 19 + Vite + TailwindCSS SPA
```

**Data Flow:**
```
Pilgrim Device → React Frontend → Express REST API → MySQL Database
                                ↕ Socket.IO (real-time)
                           Gemini AI / Geoapify / Cloudinary
```

---

## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:

| Tool | Version | Purpose |
|---|---|---|
| [Node.js](https://nodejs.org) | `>= 18.x` | Backend & frontend runtime |
| [npm](https://npmjs.com) | `>= 9.x` | Package manager |
| [MySQL](https://mysql.com) | `>= 8.0` | Database (local) |
| [Git](https://git-scm.com) | Latest | Version control |

---

### Environment Setup

> ⚠️ **Important:** Never commit real credentials. Always use `.env` files which are git-ignored.

**Step 1:** Clone the repository
```bash
git clone https://github.com/Harsh-2006-git/Smart-Pilgrims-Assistant-App.git
cd Smart-Pilgrims-Assistant-App
```

**Step 2:** Copy sample env files and fill in your credentials:
```bash
# Backend
cp Backend/.Sampleenv Backend/.env

# Frontend
cp Frontend/.env.sample Frontend/.env
```

---

### Backend Setup

```bash
cd Backend

# Install dependencies
npm install

# Seed zone data (first time only)
npm run seed

# Start development server (with auto-reload)
npm run dev

# OR start production server
npm start
```

The backend will start at **`http://localhost:3001`**

---

### Frontend Setup

```bash
cd Frontend

# Install dependencies
npm install

# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

The frontend will start at **`http://localhost:5173`**

---

## 🔑 Environment Variables Reference

### Backend — `Backend/.env`

```bash
# =========================================
# 🌐 Application Configuration
# =========================================

ADMIN_EMAIL=your-admin-email@example.com


# =========================================
# ☁️ Cloudinary Configuration
# =========================================
# Used for: Profile photos, Lost & Found images, Parking slot images
# Sign up at: https://cloudinary.com

CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_URL=cloudinary://your_api_key:your_api_secret@your_cloud_name


# =========================================
# 🗄️ Database Configuration
# =========================================
# DB_MODE: "local" for local MySQL, "cloud" for remote/Aiven MySQL

DB_MODE=local

# --- Local MySQL ---
DB_USER_LOCAL=root
DB_PASSWORD_LOCAL=your_mysql_password
DB_HOST_LOCAL=localhost
DB_PORT_LOCAL=3306
DB_NAME_LOCAL=ujjain

# --- Cloud MySQL (Aiven / PlanetScale etc.) ---
# DATABASE_URL=mysql://username:password@host:port/database_name
# DB_SSL=true
# DB_CA_CERT_PATH=./ca.pem


# =========================================
# 🤖 Gemini AI Configuration
# =========================================
# Get API key at: https://aistudio.google.com/app/apikey

GEMINI_API_KEY=your_gemini_api_key
GEMINI_API_KEY_BACKUP=your_backup_gemini_api_key


# =========================================
# 📍 Geoapify API (Nearby Services Map)
# =========================================
# Sign up at: https://www.geoapify.com

GEOAPIFY_API_KEY=your_geoapify_api_key


# =========================================
# 🔐 Google OAuth Configuration
# =========================================
# Create OAuth credentials at: https://console.cloud.google.com/apis/credentials

GOOGLE_CLIENT_ID=your_google_client_id.apps.googleusercontent.com
GOOGLE_CLIENT_SECRET=GOCSPX-your_google_client_secret

# Frontend Google Client ID (same value as GOOGLE_CLIENT_ID)
VITE_GOOGLE_CLIENT_ID=your_google_client_id.apps.googleusercontent.com


# =========================================
# 🔑 Authentication / JWT
# =========================================
# Generate secure secrets with:
# node -e "console.log(require('crypto').randomBytes(64).toString('hex'))"

JWT_SECRET=your_64_character_hex_jwt_secret
REFRESH_TOKEN_SECRET=your_64_character_hex_refresh_token_secret


# =========================================
# 🔎 SerpAPI (Web Search for AI Chatbot)
# =========================================
# Sign up at: https://serpapi.com

SERP_API_KEY=your_serp_api_key


# =========================================
# 📧 SMTP / Email Configuration
# =========================================
# Used for: OTP emails, SOS alerts, booking confirmations

SMTP_HOST=smtp.hostinger.com        # or smtp.gmail.com
SMTP_PORT=465
SMTP_SECURE=true
SMTP_USER=your_email@example.com
SMTP_PASS=your_smtp_password_or_app_password


# =========================================
# 🌍 Frontend API URL
# =========================================

VITE_API_URL=http://localhost:3001
# VITE_API_URL=https://your-backend-render-url.onrender.com   ← for production
```

---

### Frontend — `Frontend/.env`

```bash
# =========================================
# 🌍 API Base URL
# =========================================

VITE_API_URL=http://localhost:3001
# VITE_API_URL=https://your-backend-url.onrender.com


# =========================================
# 🔐 Google OAuth (Frontend)
# =========================================

VITE_GOOGLE_CLIENT_ID=your_google_client_id.apps.googleusercontent.com
```

> 💡 All frontend environment variables **must** be prefixed with `VITE_` to be exposed to the browser by Vite.

---

## 📡 API Routes Reference

All API endpoints are prefixed with `/api/v1/`

| Route Prefix | Purpose |
|---|---|
| `/api/v1/auth` | Registration, Login, Google OAuth, JWT refresh |
| `/api/v1/zone` | Zone data, QR scan, history, GPS location recording |
| `/api/v1/lost` | Lost & Found item registration and lookup |
| `/api/v1/ticket` | Temple ticket booking and management |
| `/api/v1/admin` | Admin dashboard: users, alerts, SOS, reports |
| `/api/v1/parking` | Parking slot listing, search, booking |
| `/api/v1/booking` | Parking booking management |
| `/api/v1/family` | Family member association and tracking |
| `/api/v1/nearby` | Nearby services (temples, hospitals, hotels) via Geoapify |
| `/api/v1/chatbot` | Gemini AI chatbot endpoints |
| `/api/v1/location` | Real-time GPS location logging |
| `/api/v1/crowd` | YOLOv8 crowd detection analysis |

---

## 🛠️ Tech Stack

### Backend
| Technology | Purpose |
|---|---|
| **Node.js + Express 5** | REST API server |
| **Sequelize + MySQL2** | ORM & database layer |
| **Socket.IO** | Real-time bidirectional communication |
| **Google Gemini AI** | AI chatbot & yatra planner |
| **Cloudinary** | Image upload & CDN |
| **Nodemailer** | Email notifications & OTPs |
| **Google Auth Library** | OAuth 2.0 authentication |
| **JWT** | Stateless authentication tokens |
| **Multer** | File upload middleware |
| **Helmet + CORS** | Security middleware |
| **QRCode** | QR code generation for pilgrims |
| **Razorpay** | Payment gateway integration |

### Frontend
| Technology | Purpose |
|---|---|
| **React 19 + Vite** | UI framework & build tool |
| **TailwindCSS 4** | Utility-first styling |
| **React Router DOM 7** | Client-side routing |
| **Leaflet + React-Leaflet** | Interactive maps |
| **Socket.IO Client** | Real-time data updates |
| **Framer Motion** | Animations & transitions |
| **Recharts** | Data visualization |
| **TensorFlow.js + COCO-SSD** | Client-side crowd detection |
| **jsQR** | QR code scanning in browser |
| **React Hook Form + Zod** | Form management & validation |
| **Radix UI** | Accessible UI primitives |
| **Lucide React** | Icon library |
| **i18next** | Internationalization & multilingual |
| **Firebase** | Push notifications |
| **@react-oauth/google** | Google Sign-In |

---

## 📁 Project Structure

```
Smart-Pilgrims-Assistant-App/
│
├── Backend/
│   ├── AI_Core/              # YOLOv8 crowd detection Python integration
│   ├── config/               # Database connection & configuration
│   ├── controllers/          # Route handler logic
│   │   ├── adminController.js
│   │   ├── authController.js
│   │   ├── zoneController.js
│   │   └── ...
│   ├── middlewares/          # Auth guards, error handler, rate limiter
│   ├── models/               # Sequelize ORM models
│   ├── routes/               # Express route definitions
│   ├── socket/               # Socket.IO event handlers
│   ├── uploads/              # Local file storage (dev only)
│   ├── utils/                # Helper utilities
│   ├── .Sampleenv            # ← Template for your .env file
│   ├── ca.pem                # SSL certificate for cloud DB
│   ├── index.js              # App entry point
│   ├── vercel.json           # Vercel serverless config
│   └── package.json
│
├── Frontend/
│   ├── public/               # Static assets
│   ├── src/
│   │   ├── assets/           # Images, icons, logo
│   │   ├── components/       # Reusable UI components
│   │   │   ├── Header.jsx
│   │   │   ├── Footer.jsx
│   │   │   └── chat/
│   │   ├── config/           # API base URL config
│   │   ├── pages/            # Route-level page components
│   │   │   ├── index1.jsx         # Home page
│   │   │   ├── auth.jsx           # Login / Register
│   │   │   ├── density.jsx        # Zone crowd monitoring
│   │   │   ├── ticket.jsx         # Temple ticketing
│   │   │   ├── LostAndFound.tsx   # Lost & Found
│   │   │   ├── MapPage.jsx        # Interactive map
│   │   │   ├── FamilyMode.jsx     # Family tracking
│   │   │   ├── AdminPage.jsx      # Admin dashboard
│   │   │   ├── profile.jsx        # User profile
│   │   │   ├── ChatbotPage.jsx    # AI chatbot
│   │   │   ├── LiveDarshan.tsx    # Live streaming
│   │   │   ├── CrowdDetector.jsx  # AI crowd detection
│   │   │   └── Parking/           # Parking module
│   │   └── temple1/          # Scroll-animation hero images
│   ├── .env.sample           # ← Template for your .env file
│   ├── index.html
│   ├── vite.config.js
│   ├── vercel.json           # Vercel SPA routing config
│   └── package.json
│
├── .github/                  # Issue & PR templates
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── INSTALLATION.md
├── .gitignore
└── readme.md
```

---

## 🌐 Deployment

### Backend → Render / Railway

1. Push code to GitHub
2. Connect repo to [Render](https://render.com) or [Railway](https://railway.app)
3. Set **all backend environment variables** in the platform dashboard
4. Set `DB_MODE=cloud` and configure your cloud MySQL credentials
5. Set start command: `npm start`

### Frontend → Vercel

1. Connect your GitHub repo to [Vercel](https://vercel.com)
2. Set **Root Directory** to `Frontend`
3. Add environment variables:
   - `VITE_API_URL` → your deployed backend URL
   - `VITE_GOOGLE_CLIENT_ID` → your Google OAuth client ID
4. Vercel auto-detects Vite — deploy!

> The `Frontend/vercel.json` already handles SPA routing rewrites.

---

### Google OAuth Setup (Required)

1. Go to [Google Cloud Console](https://console.cloud.google.com/apis/credentials)
2. Create a new **OAuth 2.0 Client ID** (Web Application)
3. Add **Authorized JavaScript Origins:**
   - `http://localhost:5173`
   - `https://your-frontend-domain.vercel.app`
4. Add **Authorized Redirect URIs:**
   - `http://localhost:3001/api/v1/auth/google/callback`
   - `https://your-backend-url.com/api/v1/auth/google/callback`
5. Copy the **Client ID** and **Client Secret** to your `.env` files

---

## 🤝 Contributing

1. **Fork** the repository
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m "feat: add your feature"`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a **Pull Request** to `main`

For detailed contribution guidelines, see [CONTRIBUTING.md](./CONTRIBUTING.md).

> ⚠️ The `main` branch has branch protection rules. All changes must go through a Pull Request.

---

<div align="center">

**Built with ❤️ for Bharat's 50M+ pilgrims**

*Faith • Peace • Devotion*

🕉️ *Jay Mahakal* 🕉️

</div>
