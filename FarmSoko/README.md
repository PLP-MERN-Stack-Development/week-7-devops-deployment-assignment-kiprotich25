# 🥬 FarmSoko

**FarmSoko** is a full-stack MERN marketplace for agricultural products. It allows users to post, browse, and manage farm produce in real-time. The app includes product categories, search and filter, image upload, and a personal dashboard.

---

## Deployment links

- Frontend: https://farm-soko.vercel.app
- Backend API: https://farm-soko-api.onrender.com

## 📸 Screenshots

| Home Page | Product Listing | My Products |
|-----------|-----------------|-------------|
| ![Home](./screenshots/home.png) | ![Products](./screenshots/products.png) | ![My Products](./screenshots/my-products.png) |

---

## 📦 Features

- 🔐 Authentication & Authorization
- 📤 Product posting with image upload (Cloudinary)
- 🔍 Search and category filtering
- 🧾 My Products view (edit/delete only your own)
- ⚡ Realtime feedback and alerts
- 📱 Fully responsive UI (ShadCN + Tailwind CSS)

---

## 🧪 Tech Stack

| Tech                      | Role                |
|---------------------------|---------------------|
| MongoDB                   | NoSQL Database      |
| Express.js                | Backend Framework   |
| React.js                  | Frontend UI         |
| Node.js                   | Server Runtime      |
| Tailwind CSS + ShadCN     | Styling & Components|
| Cloudinary                | Image Storage       |
| JWT                       | User Authentication |
| Vite                      | React Build Tool    |
| Vercel                    | Frontend Hosting    |
| Render                    | Backend Hosting     |

---

## 🛠️ Setup Instructions

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/farmsoko.git
cd farmsoko
Set up environment variables

Create two .env files:

     backend/.env:
     .env
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret

frontend/.env:
     .env
VITE_API_BASE_URL=https://your-backend-url.com/api

Install dependencies

pnpm install
cd backend && pnpm install
cd ../frontend && pnpm install
Run the app locally


# In /backend
pnpm run dev

# In /frontend
pnpm run dev
🔬 Testing
✅ Unit & Integration tests using Jest and Supertest

✅ MongoDB Memory Server for in-memory testing


To run backend tests:
cd backend
pnpm test


To run frontend tests:
cd frontend
pnpm test

⚙️ Architecture Overview
Monorepo with separate frontend/ and backend/
RESTful API with Express and JWT-based auth
Frontend with Vite + React + Tailwind + ShadCN
CI/CD via GitHub Actions


🎥 Demo Video
🎬 Watch the 5–10 min demo here

📚 API Documentation
See backend/docs/API.md for detailed route info, request formats, and examples.

🙋‍♀️ Author
Your Name
GitHub · Portfolio

🏁 License
MIT License
