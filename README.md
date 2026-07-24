<div align="center">

<h1>AI-Powered College Discovery & Admission Intelligence Platform</h1>

<p>
A modern full-stack platform that helps students discover engineering colleges, compare institutions, predict admission chances, and manage personalized college preferences.
</p>

<p>

![Next.js](https://img.shields.io/badge/Next.js-15-black?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5-blue?style=for-the-badge&logo=typescript)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4-38BDF8?style=for-the-badge&logo=tailwind-css)
![Prisma](https://img.shields.io/badge/Prisma-ORM-2D3748?style=for-the-badge&logo=prisma)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-4169E1?style=for-the-badge&logo=postgresql)
![NextAuth](https://img.shields.io/badge/Auth-NextAuth-000000?style=for-the-badge)
![Vercel](https://img.shields.io/badge/Deploy-Vercel-black?style=for-the-badge&logo=vercel)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</p>

🌐 **Live Demo**

https://college-discovery-platform-seven-gamma.vercel.app

</div>

---

# 📖 Overview

Choosing the right engineering college is one of the most important decisions for students. College Compass simplifies this process through intelligent search, AI-assisted recommendations, admission prediction, and side-by-side comparison of colleges.

The platform provides a fast, responsive, and modern experience built with the latest web technologies while maintaining scalability and clean architecture.

---

# ✨ Features

## 🏫 College Discovery

- Search colleges instantly
- Browse top engineering institutes
- Filter by location
- Filter by fees
- Filter by ranking
- Filter by average package
- Detailed college profiles

---

## 🤖 AI Admission Predictor

Predict admission chances using:

- JEE Main Percentile
- Category
- State Quota
- College Preferences
- Historical Cutoff Trends

---

## 📊 College Comparison

Compare multiple colleges simultaneously.

Comparison includes:

- NIRF Ranking
- Average Package
- Highest Package
- Tuition Fees
- Hostel Fees
- Placement Percentage
- Location
- Branch Availability

---

## 👤 User Authentication

- Secure Login
- User Registration
- Protected Dashboard
- Personalized Experience

---

## ❤️ Saved Colleges

Users can

- Bookmark colleges
- Save predictions
- View recent searches
- Manage preferences

---

## 📱 Responsive Design

Works perfectly on

- Desktop
- Laptop
- Tablet
- Mobile

---

# 🖼 Screenshots

## Home Page

> Add screenshot here

```
public/screenshots/home.png
```

---

## Admission Predictor

```
public/screenshots/predictor.png
```

---

## Compare Colleges

```
public/screenshots/compare.png
```

---

## Dashboard

```
public/screenshots/dashboard.png
```

---

## Login

```
public/screenshots/login.png
```

---

# 🎥 Demo

Add a 30-second GIF.

```
public/demo.gif
```

Recommended flow

- Open Website
- Search College
- Predict Admission
- Compare Colleges
- Dashboard

---

# 🏗 System Architecture

```
                    User
                      │
                      ▼
             Next.js Frontend
                      │
                      ▼
              API Routes (REST)
                      │
                      ▼
              Business Logic
                      │
                      ▼
                 Prisma ORM
                      │
                      ▼
              PostgreSQL Database
                      │
                      ▼
          Admission Prediction Engine
```

---

# ⚙ Tech Stack

| Layer | Technology |
|---------|------------|
| Frontend | Next.js App Router |
| Language | TypeScript |
| Styling | Tailwind CSS |
| Authentication | NextAuth.js |
| Database | PostgreSQL |
| ORM | Prisma |
| Deployment | Vercel |
| Version Control | Git + GitHub |

---

# 📂 Project Structure

```
College-Compass/

│
├── prisma/
│   ├── schema.prisma
│
├── public/
│   ├── screenshots/
│   └── demo.gif
│
├── src/
│
│   ├── app/
│   │
│   ├── components/
│   │
│   ├── features/
│   │
│   ├── lib/
│   │
│   ├── services/
│   │
│   ├── hooks/
│   │
│   ├── types/
│   │
│   ├── utils/
│   │
│   └── middleware.ts
│
├── package.json
├── tsconfig.json
└── README.md
```

---

# 🗄 Database Design

```
Users
│
├── id
├── name
├── email
└── password

        │

Predictions
│
├── percentile
├── category
├── predictedCollege
└── createdAt

        │

Saved Colleges
│
├── collegeId
├── userId
└── createdAt

        │

Colleges
│
├── name
├── ranking
├── location
├── fees
├── package
└── cutoff
```

---

# 🔌 API Endpoints

## Authentication

```
POST /api/auth/register

POST /api/auth/login

POST /api/auth/logout
```

---

## Colleges

```
GET /api/colleges

GET /api/college/:id

GET /api/search
```

---

## Prediction

```
POST /api/predict
```

---

## Dashboard

```
GET /api/dashboard

GET /api/saved
```

---

# 🚀 Installation

## Clone Repository

```bash
git clone https://github.com/cheelaakhil/college-compass.git
```

---

## Enter Folder

```bash
cd college-compass
```

---

## Install Dependencies

```bash
npm install
```

---

## Environment Variables

Create a `.env`

```env
DATABASE_URL="postgresql://username:password@localhost:5432/college_compass"

NEXTAUTH_SECRET="your_secret"

NEXTAUTH_URL="http://localhost:3000"
```

---

## Prisma

```bash
npx prisma migrate dev

npx prisma generate
```

---

## Run Development Server

```bash
npm run dev
```

Visit

```
http://localhost:3000
```

---

# 🌟 Future Roadmap

- AI College Recommendation Engine
- AI Career Counsellor
- Scholarship Recommendation
- Branch Predictor
- Placement Analytics
- Resume Builder
- AI Chatbot
- Voice Assistant
- College Reviews
- Student Community

---

# 📈 Performance Goals

- Lighthouse Performance ≥95
- Accessibility ≥100
- SEO ≥100
- Best Practices ≥100

---

# 🧪 Testing

```bash
npm run lint

npm run build

npm run test
```

---

# 🤝 Contributing

1. Fork Repository

2. Create Branch

```bash
git checkout -b feature/new-feature
```

3. Commit Changes

```bash
git commit -m "feat: add new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open Pull Request

---

# 👨‍💻 Developer

**Akhil Cheela**

Computer Science Engineering Student

Institute of Aeronautical Engineering

GitHub

https://github.com/cheelaakhil

LinkedIn

https://www.linkedin.com/in/akhil-cheela-8a72a0292/

Email

akhilcheela@gmail.com

---

# 📜 License

This project is licensed under the MIT License.

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a Star.

Made with ❤️ using Next.js, TypeScript, Prisma, PostgreSQL and Tailwind CSS.

</div>Platform/issues).

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
