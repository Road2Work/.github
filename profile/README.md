# 🚀 Road2Work.id — AI Career Readiness Platform

<div align="center">

<!-- Optional: replace with your logo -->

<img src="https://via.placeholder.com/180x80?text=Road2Work.id" alt="Road2Work.id Logo" />

### **Your Roadmap to a Better Career**

**From real experience to career readiness.**

</div>

---

## 🎯 About The Project

**Road2Work.id** adalah **AI Career Readiness Platform** yang membantu mahasiswa tingkat akhir, fresh graduate, career switcher, dan pencari kerja pemula mempersiapkan diri menuju dunia kerja secara lebih terarah.

Road2Work.id tidak hanya berfokus pada latihan interview, tetapi membantu user untuk:

* 🧠 membangun profil profesional dari CV atau profil singkat,
* 🎯 menemukan role yang relevan dengan skill dan pengalaman,
* 🎙️ latihan interview adaptif dengan AI HRD,
* 📊 mendapatkan feedback berbasis evidence,
* 🚀 melihat progress kesiapan karier melalui Career Readiness Dashboard.

Core flow Road2Work.id:

```text
Profile → Role → Practice → Feedback → Improve
```

---

## 🌟 Product Vision

Banyak kandidat pemula sebenarnya sudah memiliki pengalaman seperti project kampus, organisasi, bootcamp, freelance, magang, atau tugas akhir. Namun, pengalaman tersebut sering belum tersusun menjadi bukti kompetensi yang kuat saat membuat CV maupun menghadapi interview.

**Road2Work.id hadir untuk membantu user mengubah pengalaman nyata menjadi sinyal kompetensi yang lebih jelas, terukur, dan relevan dengan kebutuhan dunia kerja.**

> Road2Work.id bukan sekadar mock interview tool.
> Road2Work.id adalah roadmap untuk membangun career readiness.

---

## 💡 Problem Statement

Bagaimana Road2Work.id dapat membantu user mengubah pengalaman nyata menjadi profil profesional, memahami role yang relevan, menjawab interview berbasis bukti, dan mengetahui langkah perbaikan karier yang jelas?

---

## 👥 Target Users

Road2Work.id dibangun untuk kandidat yang sedang membangun arah karier, terutama:

* 🎓 **Mahasiswa Tingkat Akhir**
  Punya project, organisasi, atau pengalaman kampus, tetapi bingung cara menjelaskannya secara profesional.

* 💼 **Fresh Graduate**
  Sudah punya CV, tetapi belum yakin apakah pengalaman dan jawaban interview sudah cukup kuat.

* 🔄 **Career Switcher Pemula**
  Ingin pindah bidang dan perlu menghubungkan pengalaman lama dengan role baru.

* 🔍 **Pencari Kerja Awal**
  Butuh latihan, feedback, dan arahan sebelum melamar kerja.

---

## ✨ Main Features

### 1. 🧠 Build Your Professional Profile

### **Professional Profile Intelligence**

Upload CV atau isi profil singkat. Road2Work membantu membaca pengalaman user menjadi:

* professional summary,
* skill list,
* tools,
* achievement signals,
* evidence,
* profile completeness,
* evidence score.

---

### 2. 🎯 Find Your Best-Fit Role

### **Role Fit Recommendation**

Road2Work membantu user memahami role yang relevan berdasarkan profil, skill, dan evidence.

Pada MVP terdapat dua jalur utama:

#### 📄 Upload CV Path

```text
Upload CV → AI Extract Profile → Review Profile → Role Fit Ranking → Confirm Role → Interview → Dashboard
```

Cocok untuk user yang sudah punya CV dan pengalaman terdokumentasi.

#### ✍️ Manual Profile Path

```text
Pilih Domain → Role Family → Target Role → Isi Profil → Review Profile → Interview → Dashboard
```

Cocok untuk user yang belum siap upload CV atau ingin mulai dari profil singkat.

---

### 3. 🎙️ Practice with Adaptive AI HRD

### **Adaptive Voice Interview**

Road2Work menyediakan latihan interview berbasis suara dengan AI HRD.

Fitur utama:

* AI HRD mengajukan pertanyaan adaptif,
* mic otomatis aktif saat user menjawab,
* user memiliki waktu 90 detik untuk menjawab,
* jawaban diproses melalui speech-to-text,
* AI dapat memberikan clarification question,
* practice memory digunakan untuk sesi interview berikutnya.

Interview state:

```text
Idle → Asking → Listening → Thinking → Clarifying → Completed
```

---

### 4. 📊 Get Evidence-Based Feedback

### **Evidence-Based Feedback**

Jawaban user dievaluasi berdasarkan:

* role relevance,
* struktur jawaban,
* clarity,
* evidence,
* tools yang digunakan,
* kontribusi pribadi,
* impact,
* weakness yang ditemukan.

Output feedback:

* answer score,
* score breakdown,
* detected weaknesses,
* stronger answer suggestion,
* clarification decision,
* latest feedback.

---

### 5. 🚀 Track Your Career Readiness

### **Career Readiness Dashboard**

Dashboard menjadi pusat hasil dan perkembangan user setelah interview.

Dashboard menampilkan:

* Career Readiness Score,
* Evidence Score,
* Role Fit Score,
* Interview Readiness,
* Profile Completeness,
* Strengths,
* Gaps,
* Latest Feedback,
* Activity Timeline,
* Next Best Actions.

---

## 🧩 MVP Scope

### ✅ Included in MVP

* Landing page
* Login & signup
* Career onboarding
* Upload CV path
* Manual profile path
* Profile review
* Role fit recommendation
* Interview onboarding
* Adaptive voice interview
* Speech-to-text
* Clarification question
* Interview result
* Career Readiness Dashboard
* Admin panel basic
* Backend API integration
* AI service integration
* Data science dashboard / analytics support

### ❌ Not Included in MVP

* Job portal real-time
* Apply job langsung ke perusahaan
* Payment / subscription
* Live AI avatar dengan lip sync
* Webcam analysis
* Emotion detection
* Mentor marketplace
* Full CV builder
* Mobile native app

---

## 🛠️ Tech Stack

### 🌐 Frontend

* Next.js
* TypeScript
* Tailwind CSS
* Axios / Fetch API
* TanStack Query
* Responsive Web Design
* Figma UI Mockup

### 🧩 Backend

* Node.js
* Express.js
* TypeScript
* RESTful API
* PostgreSQL
* Drizzle ORM
* Authentication & Authorization
* API Gateway for AI Service

### 🤖 Artificial Intelligence

* Python
* FastAPI
* TensorFlow / Keras
* Speech-to-Text
* NLP-based evaluation
* Generative AI support
* TensorBoard monitoring
* Model inference API

### 📊 Data Science

* Data gathering
* Data cleaning
* Feature engineering
* Exploratory Data Analysis
* Model evaluation
* A/B testing
* Streamlit dashboard
* Data visualization

### 🚀 Deployment

* Frontend: Vercel / Netlify
* Backend: Render / Railway
* AI Service: Render / Railway
* Dashboard: Streamlit Cloud
* Database: PostgreSQL

---

## 🏗️ System Architecture

```mermaid
graph TD
    A[User Browser] --> B[Next.js Frontend]
    B --> C[Express.js Backend API]
    C --> D[PostgreSQL Database]
    C --> E[FastAPI AI Service]
    E --> F[Profile Extraction]
    E --> G[Role Fit Scoring]
    E --> H[Speech-to-Text]
    E --> I[Interview Question Generator]
    E --> J[Answer Evaluation]
    E --> K[Feedback Generator]
```

### Architecture Principle

Frontend tidak memanggil AI service secara langsung. Backend berperan sebagai API gateway untuk mengelola:

* authentication,
* user profile,
* role fit,
* interview session,
* interview result,
* dashboard data,
* quota,
* admin data.

AI Service menangani proses:

* profile extraction,
* role fit scoring,
* speech-to-text,
* adaptive question generation,
* clarification question,
* answer evaluation,
* feedback generation.

---

## 📁 Project Structure

Contoh struktur repository:

```text
road2work/
├── frontend/
│   ├── app/
│   ├── components/
│   ├── services/
│   └── styles/
│
├── backend/
│   ├── src/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── db/
│
├── ai-service/
│   ├── app/
│   ├── models/
│   ├── pipelines/
│   └── inference/
│
├── data-science/
│   ├── notebooks/
│   ├── datasets/
│   └── streamlit/
│
├── docs/
│   ├── SRS.md
│   ├── API_CONTRACT.md
│   ├── OVERVIEW.md
│   └── USER_GUIDELINE.md
│
└── README.md
```

---

## 🚀 Getting Started

### 1. Clone Repository

```bash
git clone https://github.com/your-username/road2work.git
cd road2work
```

---

### 2. Run Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend will run on:

```text
http://localhost:3000
```

---

### 3. Run Backend

```bash
cd backend
npm install
npm run dev
```

Backend will run on:

```text
http://localhost:5000
```

---

### 4. Run AI Service

```bash
cd ai-service
python -m venv venv
```

For Windows:

```bash
venv\Scripts\activate
```

For Mac/Linux:

```bash
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run FastAPI service:

```bash
uvicorn app.main:app --reload
```

AI Service will run on:

```text
http://localhost:8000
```

---

### 5. Run Data Science Dashboard

```bash
cd data-science/streamlit
streamlit run app.py
```

---

## 🔐 Environment Variables

### Frontend `.env`

```env
NEXT_PUBLIC_API_BASE_URL=http://localhost:5000/api/v1
```

### Backend `.env`

```env
PORT=5000
DATABASE_URL=postgresql://user:password@localhost:5432/road2work
JWT_SECRET=your_jwt_secret
AI_SERVICE_URL=http://localhost:8000/v1
```

### AI Service `.env`

```env
MODEL_PATH=./models/model.keras
STT_MODEL=base
GENAI_API_KEY=your_api_key
```

---

## 🔌 API Overview

### Auth

```text
POST /api/v1/auth/signup
POST /api/v1/auth/login
GET  /api/v1/me
```

### Profile

```text
POST  /api/v1/profiles/cv
POST  /api/v1/profiles/manual
GET   /api/v1/profiles/:profileId
PATCH /api/v1/profiles/:profileId
POST  /api/v1/profiles/:profileId/confirm
```

### Role Fit

```text
POST /api/v1/role-fit/generate-ranking
POST /api/v1/role-fit/score
POST /api/v1/role-fit/confirm
```

### Interview

```text
POST /api/v1/interviews/sessions
GET  /api/v1/interviews/sessions/:sessionId
POST /api/v1/interviews/sessions/:sessionId/voice-answer
GET  /api/v1/interviews/sessions/:sessionId/result
```

### Dashboard

```text
GET /api/v1/dashboard
```

### Admin

```text
GET    /api/v1/admin/users
GET    /api/v1/admin/analytics
POST   /api/v1/admin/domains
PATCH  /api/v1/admin/domains/:id
DELETE /api/v1/admin/domains/:id
POST   /api/v1/admin/roles
PATCH  /api/v1/admin/roles/:id
DELETE /api/v1/admin/roles/:id
```

---

## 🧪 Testing & Validation

Validasi MVP dilakukan melalui:

* UI/UX testing,
* API integration testing,
* AI service testing,
* interview flow testing,
* dashboard output checking,
* data pipeline validation,
* TensorBoard model tracking,
* internal demo flow validation.

---

## 📈 Success Metrics

Beberapa indikator keberhasilan MVP:

* ✅ Core flow berjalan end-to-end
* ✅ User dapat masuk dari onboarding hingga dashboard
* ✅ Dua jalur onboarding tersedia: Upload CV Path dan Manual Profile Path
* ✅ Adaptive interview dapat memproses jawaban user
* ✅ Feedback berbasis evidence berhasil ditampilkan
* ✅ Dashboard menampilkan score, strengths, gaps, dan next actions
* ✅ Frontend, backend, AI service, dan database terintegrasi

---

## 👥 Team Members

| Learning Path        | Cohort ID       | Name                              | GitHub                              | LinkedIn                                      |
|---------------------|----------------|-----------------------------------|-------------------------------------|-----------------------------------------------|
| Fullstack Developer | CFCC560D6Y0640 | Alvano Hastagina                  | [GitHub](https://github.com/alvanochi) | [LinkedIn](https://linkedin.com/in/alvanoh)   |
| Fullstack Developer | CFCC676D6Y1544 | Yosua Immanuel Hizkya Kristiawan  | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| AI Engineer         | CACC149D6Y0561 | Muhammad Adil Imamul Haq Mubarak  | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| AI Engineer         | CACC307D6X0932 | Diva Syabina Putri                | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| Data Scientist      | CDCC295D6X1246 | Nurul Ainil Fitri                 | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
| Data Scientist      | CDCC290D6X1902 | Addya Virna Amany                 | [GitHub](https://github.com/)       | [LinkedIn](https://www.linkedin.com/in/)      |
---



## 📚 Documentation

Dokumentasi pendukung:

* 📌 `README.md` — setup dan cara menjalankan project
* 📄 `SRS.md` — Software Requirements Specification
* 🧭 `OVERVIEW.md` — gambaran produk Road2Work.id
* 🔌 `API_CONTRACT.md` — dokumentasi endpoint
* 👤 `USER_GUIDELINE.md` — panduan penggunaan website

---

## 🙏 Acknowledgments

Project ini dikembangkan sebagai bagian dari:

* Coding Camp 2026 powered by DBS Foundation
* Dicoding Indonesia
* Capstone Project CC26-PSU050
* Theme: Future-Ready Work & Economy

---

## 📞 Contact

* Email: [road2work@gmail.com](mailto:road2work@gmail.com)
* GitHub: https://github.com/your-username/road2work
* LinkedIn: https://linkedin.com/company/road2work

---


<div align="center">

### 🚀 Road2Work.id

**Your Roadmap to a Better Career**

Dibuat dengan ❤️ oleh Tim CC26-PSU050

</div>
