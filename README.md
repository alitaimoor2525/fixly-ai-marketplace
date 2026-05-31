# 🔧 Fixly — AI-Powered Home Services Marketplace

> A full-featured, multi-role web marketplace connecting customers 
> with verified home service professionals — powered by AI.

![React](https://img.shields.io/badge/React.js-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)
![Framer](https://img.shields.io/badge/Framer_Motion-black?style=flat&logo=framer&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-22B5BF?style=flat&logoColor=white)

---

## 📌 What is Fixly?

Fixly is a production-grade home services marketplace — 
think Urban Company or Taskrabbit — built for the Pakistani 
market. It connects customers who need home services 
(plumbing, electrical, AC repair, cleaning, carpentry, etc.) 
with verified, skilled service professionals.

What makes Fixly different: **AI is at its core.**

---

## 👥 Three Complete Role Portals

### 🏠 Customer Portal
- Browse 12 service categories
- Post job requests with budget & urgency
- Receive & compare quotes from workers
- Real-time job tracking with timeline view
- Interactive map showing nearby available workers
- Rate & review completed services
- Full job history & chat system
- Emergency service requests

### 🔨 Service Provider (Worker) Portal
- Personalized dashboard with active jobs
- Incoming job requests with accept/reject flow
- Quote submission with custom pricing
- AI Skill Evaluation — upload demo video, 
  get scored & earn skill badge
- Weekly earnings chart & performance analytics
- Profile verification system

### 👨‍💼 Admin Portal
- Complete platform oversight dashboard
- User management (customers + workers)
- All bookings & transaction monitoring
- Service category management
- Platform-wide revenue & growth analytics
- City-wise heatmap & KPI tracking

---

## 🤖 AI Features

### Nova AI Chatbot
- NLP-based intent detection
- Identifies service type from natural language
- Redirects to relevant categories automatically
- Handles emergency service routing
- Available on every page via floating button

### AI Skill Evaluation System
- Workers upload skill demonstration videos
- Simulates Twelve Labs video analysis
- Returns frame-by-frame scored segments
- Detects safety violations & best practices
- Awards skill badges: Master / Experienced / Competent

---

## ⚡ Key Features

- **Emergency Service Page** — 6 emergency types, city selector, urgency banner, instant dispatch CTA
- **Interactive Map View** — worker pins with availability, distance, ratings & click-to-select
- **Worker Analytics** — Recharts bar charts for earnings, jobs, ratings & service breakdown
- **Admin Analytics** — area charts for user growth, revenue trends & city-wise heatmap
- **Dark / Light Theme** — full toggle across all 25+ pages
- **Skeleton Loading States** — smooth UX on every data fetch
- **Framer Motion Animations** — page transitions & micro-interactions throughout
- **Fully Responsive** — mobile, tablet & desktop optimized

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend Framework | React.js (Vite) |
| Styling | Tailwind CSS |
| Animations | Framer Motion |
| Charts & Analytics | Recharts |
| Routing | React Router v6 |
| State Management | React Hooks |
| Icons | Lucide React |
| AI Chatbot | Custom NLP Intent Engine |
| Map View | Custom Interactive Map |

---

## 📂 Project Structure

```
fixly/
├── src/
│   ├── pages/
│   │   ├── LandingPage.jsx
│   │   ├── AISkillEvaluation.jsx
│   │   ├── Emergency.jsx
│   │   ├── customer/
│   │   │   ├── MapView.jsx
│   │   │   ├── JobRequest.jsx
│   │   │   └── ...
│   │   ├── worker/
│   │   │   ├── WorkerDashboard.jsx
│   │   │   ├── WorkerAnalytics.jsx
│   │   │   └── ...
│   │   └── admin/
│   │       ├── AdminDashboard.jsx
│   │       ├── AdminAnalytics.jsx
│   │       └── ...
│   ├── components/
│   │   ├── common/
│   │   │   ├── AIChat.jsx
│   │   │   └── ...
│   │   └── ...
│   └── App.jsx
├── public/
├── package.json
└── vite.config.js
```

---

## 🚀 How to Run

### Prerequisites
- Node.js 18+ installed
- npm or yarn

### Steps

```bash
# 1. Clone the repository
git clone https://github.com/alitaimoor2525/fixly-ai-marketplace

# 2. Navigate to project folder
cd fixly

# 3. Install dependencies
npm install

# 4. Start development server
npm run dev
```

Open `http://localhost:5173` in your browser.

### Test Credentials

| Role | Email | Password |
|------|-------|----------|
| Customer | customer@test.com | test123 |
| Worker | worker@test.com | test123 |
| Admin | admin@test.com | test123 |

---

## 📱 Pages Overview (25+)

| Section | Pages |
|---------|-------|
| Public | Landing, Login, Register, Emergency |
| Customer | Dashboard, Browse, Job Request, Map View, Chat, History, Reviews |
| Worker | Dashboard, Requests, Active Jobs, Analytics, Verification, Profile |
| Admin | Dashboard, Users, Bookings, Payments, Categories, Analytics |
| AI | Chatbot, Skill Evaluation |

---

## 🎓 Project Info

**Type:** Semester Project  
**University:** The Superior University, Lahore  
**Program:** BS Computer Science (6th Semester)  
**Developer:** Ali Taimoor

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ali-taimoor-357427312/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/alitaimoor2525)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:taimoorali659@gmail.com)

---

> *"Built to solve a real problem — connecting people with 
> skilled professionals, powered by AI."* 🔧
