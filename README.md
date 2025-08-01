# QuickAI – AI SaaS Platform

**Live Link:** [QuickAI](https://quickai-gs.vercel.app/)

QuickAI is a full-stack AI SaaS platform built using the **PERN stack (PostgreSQL, Express, React, Node.js)**. It provides users with access to a range of useful AI tools like article generation, blog title generation, image generation, background remover, object remover, and resume analyzer — all in one place.

This platform aims to simplify the process of accessing powerful AI tools. In a market saturated with numerous scattered AI applications, QuickAI brings together the most practical ones into a single, user-friendly solution. With subscription-based access, premium users can unlock advanced functionalities seamlessly.

---

## ✨ Features

* **Multiple AI Tools** in one place:

  * ✍️ Article Generator
  * 📝 Blog Title Generator
  * 🖼️ Image Generator
  * ✂️ Background Remover
  * 🧽 Object Remover
  * 📄 Resume Analyzer
* **Subscription-based Premium Access** via Clerk
* **Authentication & Account Management** with Clerk
* **Billing and Pricing Plans** integrated with Clerk’s system
* **Serverless PostgreSQL Database** powered by Neon for scalability and branching
* **Deployed** on Vercel for seamless CI/CD
* **API Integrations:**

  * Gemini Flash API (Google) for content generation
  * ClipDrop API for image generation, background removal, and object removal
* **API Testing** and validation using Postman

---

## 🧱 Tech Stack

* **Frontend:** React.js, Vite
* **Backend:** Node.js, Express.js
* **Database:** Neon (PostgreSQL serverless)
* **Authentication & Billing:** Clerk
* **AI APIs:** Gemini Flash API, ClipDrop API
* **Deployment:** Vercel
* **Tools:** Postman, Cloudinary (for media management), Multer (file uploads)

---

## 📂 Folder Structure

```
QuickAi/
├── client/               # React frontend
│   ├── public/           # Public assets
│   ├── src/
│   │   ├── assets/       # Images, icons, etc.
│   │   ├── components/   # Reusable UI components
│   │   └── pages/        # Route pages (Home, Dashboard, AI Tools, etc.)
│   └── ...               # Vite, config, etc.
├── server/               # Express backend
│   ├── configs/          # DB, Cloudinary, Multer configs
│   ├── controllers/      # Business logic
│   ├── middlewares/      # Auth middleware
│   ├── routes/           # Route handlers
│   └── server.js         # Entry point
├── logo_with_oneai.svg
└── Screenshot.png
```

---

## 🚀 Getting Started

### Prerequisites

* Node.js >= 16.x
* npm
* Vite
* PostgreSQL DB URL (Neon)
* Clerk account (for authentication & billing)
* API keys for Gemini and ClipDrop

### Clone the Repo

```bash
git clone https://github.com/yourusername/QuickAi.git
cd QuickAi
```

### Setup Client

```bash
cd client
npm install
npm run dev
```

### Setup Server

```bash
cd server
npm install
npm run dev
```

Make sure to configure environment variables as per your API keys and DB connection.

---

## 🔐 Environment Variables

Create a `.env` file in the `server/` folder with the following:

```env
PORT=5000
NEON_DB_URL=your_neon_db_url
CLERK_SECRET_KEY=your_clerk_secret_key
GEMINI_API_KEY=your_gemini_api_key
CLIPDROP_API_KEY=your_clipdrop_api_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_secret
```

---

## 📸 Screenshots

![App Screenshot](./Screenshot%202025-07-15%20000412.png)

---

## 📃 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 🙋‍♂️ Author

**Harsh Kharniwal**

* GitHub: [@harshkharniwal](https://github.com/harshkharniwal)
* LinkedIn: [Harsh Kharniwal](https://www.linkedin.com/in/harshkharniwal)

Feel free to fork the project, raise issues, or contribute improvements!
