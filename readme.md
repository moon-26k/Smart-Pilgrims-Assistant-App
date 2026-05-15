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