<div align="center">

<br/>

![AgroVision Banner](https://capsule-render.vercel.app/api?type=waving&color=0:1a6b2a,50:2d9e47,100:4ade80&height=220&section=header&text=AgroVision&fontSize=80&fontColor=ffffff&fontAlignY=38&desc=AI-Powered%20Smart%20Agriculture%20Platform&descAlignY=58&descSize=22&animation=fadeIn)

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-LIVE-00d26a?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Google-GEMINI%20VISION-4285F4?style=for-the-badge&logo=google&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/STACK-MERN-00d26a?style=for-the-badge&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/DEPLOY-VERCEL-ffffff?style=for-the-badge&logo=vercel&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/LICENSE-MIT-f97316?style=for-the-badge&labelColor=0d1117" />
</p>

<p align="center">
  <a href="https://agrovision.vercel.app">
    <img src="https://img.shields.io/badge/🌐%20LIVE%20DEMO-VISIT%20AGROVISION-00d26a?style=for-the-badge&labelColor=0d1117" />
  </a>
  <a href="https://github.com/nmanoj10/crop-disease">
    <img src="https://img.shields.io/badge/⭐%20STAR%20THIS%20REPO-f5a623?style=for-the-badge&labelColor=0d1117" />
  </a>
  <a href="https://github.com/nmanoj10/crop-disease/issues/new?template=bug_report.md">
    <img src="https://img.shields.io/badge/🐛%20REPORT%20BUG-e74c3c?style=for-the-badge&labelColor=0d1117" />
  </a>
  <a href="https://github.com/nmanoj10/crop-disease/issues/new?template=feature_request.md">
    <img src="https://img.shields.io/badge/💡%20OPEN%20ISSUE-8b5cf6?style=for-the-badge&labelColor=0d1117" />
  </a>
</p>

<br/>

> ### 🏛️ `Government Scheme Explorer for Farmers`
> **Empowering farmers with AI — detect diseases, forecast risks, and grow smarter.**

<br/>

*No expertise required. No complicated setup. Just point, scan, and grow.*

</div>

---

## 🌱 What is AgroVision?

**AgroVision** is a full-stack AI-powered smart agriculture platform that helps farmers detect crop diseases early, monitor weather risks, and improve farm productivity using machine learning and intelligent tools.

The platform provides a **complete digital ecosystem** for modern agriculture, integrating:

| 🔬 | **Real-time crop disease detection** via custom ML + Gemini Vision fallback |
|---|---|
| 🤖 | **Conversational AI farming advisor** powered by Google Gemini |
| 🌦️ | **Live weather forecasting** with crop disease risk scoring |
| 💰 | **Data-driven crop profitability** analysis and recommendations |
| 🏛️ | **Government agricultural scheme** discovery and eligibility guide |
| 💡 | **Community-driven farming innovation** and proposal board |

```
📷 Upload a leaf image  →  🧠 AI detects the disease  →  💊 Get treatment in seconds
```

---

## ✨ Core Features

| Module | Capability | Powered By |
|--------|-----------|------------|
| 🌿 **Disease Detection** | Upload leaf → instant AI diagnosis with full treatment plan | ML Model + Gemini Vision |
| 🤖 **AI Assistant** | 24/7 farming chatbot for pesticide, fertilizer & crop advice | Google Gemini AI |
| 🌦️ **Weather & Risk** | 7-day forecast + disease outbreak probability alerts | OpenWeatherMap API |
| 💰 **Income Advisor** | Profit calculator, crop recommender, seasonal yield insights | Data Analytics |
| 🏛️ **Gov. Schemes** | PM-KISAN, PMFBY, Kisan Credit Card, irrigation subsidies | Curated Database |
| 💡 **Innovation Board** | Submit, vote, and discover community farming ideas | MongoDB + React |

---

## 🔬 AI Crop Disease Detection

The disease detection pipeline combines a custom-trained CNN model with Google Gemini Vision as an intelligent fallback — delivering fast, accurate diagnoses even for rare or edge-case plant conditions.

```
User Uploads Leaf Image
        │
        ▼
☁️  Cloudinary CDN Storage
        │
        ▼
🧠  Custom ML Model — CNN Disease Classification
        │
        ├── High Confidence ──► Return diagnosis + treatment plan
        │
        └── Low Confidence ──► 🔮 Gemini Vision Analysis
                                       │
                                       ▼
                              📋 Detailed AI Report
```

**What you get with every scan:**
- ✅ Disease name & confidence score
- ✅ Severity assessment (mild / moderate / severe)
- ✅ Step-by-step organic & chemical treatment options
- ✅ Preventive care advice
- ✅ Scan history saved to your dashboard

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────┐
│         React Frontend (Vite + Tailwind CSS)         │
│                                                     │
│  Landing Page │ Dashboard │ Detect Disease           │
│  AI Assistant │ Weather   │ Income Advisor           │
│  Gov. Schemes │ Proposal Board                       │
└─────────────────────┬───────────────────────────────┘
                       │  REST API (Axios)
                       ▼
┌─────────────────────────────────────────────────────┐
│          Express.js Backend (Node.js)                │
│                                                     │
│  /detect  │  /auth   │  /weather  │  /proposals     │
│                                                     │
│  JWT Auth Middleware │ Multer + Cloudinary Upload    │
└──────┬────────┬──────────┬──────────────────────────┘
       │        │          │
       ▼        ▼          ▼
  MongoDB    Gemini     OpenWeather
   Atlas      AI          Map API
  (Data)    (Vision +   (Forecast +
            Chat)        Risk Score)
```

---

## 🧠 Tech Stack

### Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Backend
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB_Atlas-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT_Auth-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

### AI & Machine Learning
![Google Gemini](https://img.shields.io/badge/Gemini_Vision-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_AI_Chat-34A853?style=for-the-badge&logo=google&logoColor=white)
![TensorFlow](https://img.shields.io/badge/Custom_CNN_Model-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)

### External APIs & Hosting
![OpenWeatherMap](https://img.shields.io/badge/OpenWeatherMap-EB6E4B?style=for-the-badge&logo=openweathermap&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

---

## 📁 Project Structure

```
agrovision/
│
├── 📁 client/                           # React Frontend (Vite)
│   ├── 📁 public/
│   └── 📁 src/
│       ├── 📁 components/
│       │   ├── Navbar.jsx
│       │   ├── Sidebar.jsx
│       │   ├── DiseaseCard.jsx
│       │   ├── WeatherWidget.jsx
│       │   └── ChatInterface.jsx
│       ├── 📁 pages/
│       │   ├── LandingPage.jsx          # Platform intro & features
│       │   ├── Dashboard.jsx            # Scan stats & history
│       │   ├── DetectDisease.jsx        # Image upload & AI analysis
│       │   ├── AIAssistant.jsx          # Gemini chatbot interface
│       │   ├── Weather.jsx              # Forecast & risk alerts
│       │   ├── IncomeAdvisor.jsx        # Profitability tools
│       │   ├── Schemes.jsx              # Government scheme explorer
│       │   └── ProposalBoard.jsx        # Community innovations
│       ├── 📁 services/
│       │   ├── api.js                   # Axios instance + interceptors
│       │   └── auth.js                  # Token management
│       ├── App.jsx
│       └── main.jsx
│
├── 📁 server/                           # Express Backend
│   ├── 📁 controllers/
│   │   ├── detectController.js          # ML + Gemini detection logic
│   │   ├── chatController.js            # AI assistant handler
│   │   ├── weatherController.js         # OpenWeatherMap integration
│   │   └── schemeController.js          # Gov schemes data
│   ├── 📁 models/
│   │   ├── User.js                      # Mongoose user schema
│   │   ├── Scan.js                      # Disease scan history
│   │   └── Proposal.js                  # Community proposals
│   ├── 📁 routes/
│   │   ├── detect.js
│   │   ├── auth.js
│   │   ├── weather.js
│   │   └── proposals.js
│   ├── 📁 middleware/
│   │   ├── auth.js                      # JWT verification middleware
│   │   └── upload.js                    # Multer + Cloudinary handler
│   └── server.js                        # Application entry point
│
├── .env.example
├── package.json
└── README.md
```

---

## ⚡ Quick Start

### Prerequisites

| Tool | Min Version | Download |
|------|------------|---------|
| Node.js | v18+ | [nodejs.org](https://nodejs.org) |
| npm | v9+ | Bundled with Node.js |
| Git | Latest | [git-scm.com](https://git-scm.com) |

### Step 1 — Clone the Repository

```bash
git clone https://github.com/nmanoj10/crop-disease.git
cd crop-disease
```

### Step 2 — Install Dependencies

```bash
# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install
```

### Step 3 — Configure Environment Variables

```bash
# In /server directory, create .env
cp .env.example .env
```

Fill in your `.env` with:

```env
# Server
PORT=5000
NODE_ENV=development

# Database
MONGODB_URI=your_mongodb_atlas_connection_string

# Authentication
JWT_SECRET=your_super_secret_jwt_key

# AI APIs
GEMINI_API_KEY=your_google_gemini_api_key

# Cloud Storage
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

# Weather
OPENWEATHER_API_KEY=your_openweathermap_api_key
```

### Step 4 — Run the Application

```bash
# Terminal 1 — Start the backend server
cd server
npm run dev

# Terminal 2 — Start the frontend
cd client
npm run dev
```

🎉 Open [http://localhost:5173](http://localhost:5173) and start growing smarter!

---

## 🗺️ Roadmap

| Status | Feature |
|--------|---------|
| 🔜 SOON | 📱 Native mobile app (React Native) for offline-capable farms |
| 🔜 SOON | 🚁 Drone crop scanning for field-scale disease mapping |
| 🔜 SOON | 🛰️ Satellite NDVI monitoring for large-scale crop health |
| 🔜 SOON | 🧪 Soil sensor integration — NPK + pH-based recommendations |
| 🔜 SOON | 🎙️ Multilingual voice assistant (Hindi, Tamil, Telugu, Marathi) |
| 🔜 SOON | 📡 SMS disease risk alerts — no internet connection required |
| 🔜 SOON | 🤝 Peer-to-peer marketplace for farmers to buy/sell produce |
| 🔜 SOON | 🌍 Multi-region localized crop database expansion |

---

## 🤝 Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 💬 Support

Show support by ⭐ starring the repository — it keeps this project alive and growing!

<div align="center">

**Built with ❤️ for Indian Farmers**

*Empowering agriculture through artificial intelligence*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a6b2a,50:2d9e47,100:4ade80&height=100&section=footer)

</div>
