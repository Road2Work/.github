
---

<div align="center">
  <h1>🚀 Road2Work - AI Mock Interview Platform</h1>
  <p><i>Your journey to landing your dream job starts here</i></p>
</div>

# 🎯 Capstone Project — Road2Work

Welcome to **Road2Work**! 👋
Platform berbasis AI yang membantu job seeker di Indonesia mempersiapkan interview kerja secara lebih terarah, terukur, dan realistis.

---

## 🌟 Project Overview

**Road2Work** adalah aplikasi web yang menyediakan simulasi interview berbasis AI dengan alur yang menyerupai proses rekrutmen nyata di Indonesia.

User dapat:

* Latihan interview (HRD → Technical → User)
* Mendapatkan feedback otomatis berbasis AI
* Melihat progress dan peningkatan performa

Platform ini dirancang khusus dengan konteks **pasar kerja Indonesia**. 

---

## 💡 Why It Matters

Permasalahan utama job seeker di Indonesia:

* Tidak ada feedback objektif
* Kurangnya pemahaman alur interview
* Latihan tidak terstruktur
* Tools global tidak kontekstual

**Road2Work memberikan solusi:**

* 🤖 AI evaluation berbasis NLP
* 🎭 Simulasi interview realistis
* 📊 Tracking perkembangan user
* 🎯 Career-specific interview flow

---

## 🎯 Target Users

* Fresh Graduate
* Job Seeker
* Career Switcher di Indonesia

---

## 👥 Team Composition

| Role                | Jumlah | Fokus                    |
| ------------------- | ------ | ------------------------ |
| Fullstack Developer | 2      | Web app & API            |
| Data Scientist      | 2      | Data analysis & pipeline |
| AI Engineer         | 2      | Model & AI system        |

---

## 👥 Meet Our Team

Tim kami menggabungkan keahlian AI Engineer, Fullstack Developer, dan Data Science untuk membangun solusi berbasis AI yang membantu job seeker meningkatkan kesiapan interview dan peluang diterima kerja.

| Learning Path        | Cohort ID       | Name                              | GitHub                              | LinkedIn                                      |
|---------------------|----------------|-----------------------------------|-------------------------------------|-----------------------------------------------|
| Fullstack Developer | CFCC560D6Y0640 | Alvano Hastagina                  | [GitHub](https://github.com/alvanochi) | [LinkedIn](https://linkedin.com/in/alvanoh)   |
| Fullstack Developer | CFCC676D6Y1544 | Yosua Immanuel Hizkya Kristiawan  | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| AI Engineer         | CACC149D6Y0561 | Muhammad Adil Imamul Haq Mubarak  | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| AI Engineer         | CACC307D6X0932 | Diva Syabina Putri                | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| Data Scientist      | CDCC295D6X1246 | Nurul Ainil Fitri                 | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| Data Scientist      | CDCC290D6X1902 | Addya Virna Amany                 | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |

## 🛠️ Technology Stack (Based on Checklist)

### 🌐 Front-End & Back-End

* RESTful API (Express)
* Networking API Calls (Axios / Fetch)
* Module Bundler (Vite / Webpack)
* API mengikuti standar RESTful (endpoint, method, status code)
* Data storage (PostgreSQL)
* Integrasi AI/ML ke dalam aplikasi
* Stability & error handling
* Responsive Web Design (Tailwind)
* Deployment (Vercel)
* Database integration (PostgreSQL)
* UI Mockup (Figma)

---

### 🤖 Artificial Intelligence

* Model Deep Learning (TensorFlow Functional API / Subclassing)
* Custom Component:

  * Custom Layer / Loss / Callback
* Model export:

  * `.keras` / `SavedModel`
* Inference pipeline sederhana
* Integrasi model ke aplikasi (backend)
* REST API untuk model (FastAPI / Flask)
* Generative AI API (optional feature)
* TensorBoard monitoring
* Custom training loop (tf.GradientTape)

---

### 📊 Data Science

* Problem definition (business question)
* Data Wrangling end-to-end:

  * Data gathering
  * Data assessing
  * Data cleaning
* Exploratory Data Analysis (EDA)
* Data visualization & insight
* Streamlit dashboard
* Data readiness + Data Dictionary
* Feature engineering
* A/B Testing
* Dashboard deployment (Streamlit Cloud)
* Technical report (PDF)

---

## 🚀 Key Features

### 1. 🎭 Interview Simulation

* Multi-stage interview:

  * HRD
  * Technical
  * User
* Career-based questions
* Structured interview flow

### 2. 🤖 AI Evaluation Engine

* Penilaian berbasis:

  * Relevansi jawaban
  * Struktur (STAR method)
  * Kedalaman konten
* Feedback otomatis

### 3. 📊 Progress Tracking

* History interview
* Score improvement
* Insight performa user

---

## 🧩 Supported Career Paths

| Career Path              | Flow                                |
| ------------------------ | ----------------------------------- |
| Software Engineer        | HRD → Technical → User → Final      |
| Data Analyst / Scientist | HRD → Technical → Case Study → User |
| Product Manager          | HRD → Case → User → Final           |
| UI/UX Designer           | HRD → Portfolio → Challenge → User  |
| Marketing / Growth       | HRD → Campaign → User               |

---

## 🔄 Project Architecture

```mermaid
graph TD
    A[Frontend Web App] --> B[Backend API]
    B --> C[Auth Service]
    B --> D[Interview Engine]
    D --> E[Question Generator]
    D --> F[AI Evaluation Engine]
    F --> G[NLP Model (TensorFlow)]
    B --> H[Database]
```

---

## 📅 Development Roadmap

### Sprint 1 — Foundation

* Setup repo & environment
* UI + authentication
* Bank soal awal
* Basic API integration

### Sprint 2 — AI Engine

* NLP evaluation model
* Feedback generator
* Multi-stage interview flow
* Dashboard progress

### Sprint 3 — Integration

* Integrasi AI ke backend
* Optimasi API
* Testing fitur utama

### Sprint 4 — Finalization

* Bug fixing
* User testing
* UI/UX improvement
* Demo preparation

---

## ⚠️ Risks & Mitigation

| Risk                   | Mitigation              |
| ---------------------- | ----------------------- |
| Model AI kurang akurat | Iterasi + evaluasi user |
| Data kurang            | Dataset + augmentasi    |
| Timeline padat         | Fokus MVP               |

---

## 📈 Success Metrics

* ✅ 2 career path berjalan end-to-end
* ✅ AI feedback dianggap helpful oleh ≥70% user
* ✅ Response time < 5 detik
* ✅ Aplikasi stabil tanpa crash

---

## 🌱 Getting Started

### Prerequisites

* Node.js
* Python 3.9+
* TensorFlow
* PostgreSQL (optional)

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add some Feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

---

## 📞 Contact

* Email: [road2work@gmail.com](mailto:road2work@gmail.com)
* LinkedIn: [Road2Work](https://linkedin.com/road2work)

---

## 🙏 Acknowledgments

* Coding Camp Capstone Project 2026
* Komunitas Open-source

---

<div align="center">
  <p>Dibuat dengan ❤️ oleh Tim Road2Work</p>
</div>

---
