<div align="center">

  <img src="frontend/public/KKLogo.png" alt="Kumar Kosmetics Logo" width="180" />

#  Kumar Kosmetics

### _Redefining Beauty with Smart Tech & Elegance_

[![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-404D59?style=for-the-badge)](https://expressjs.com/)
[![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)](https://www.mongodb.com/)
[![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?&style=for-the-badge&logo=redis&logoColor=white)](https://redis.io/)

  <br />

  <p align="center">
    <strong>Kumar Kosmetics</strong> is not just an e-commerce store; it's a <i>digital beauty experience</i>. <br />
    Blending state-of-the-art <strong>Smart Skin Analysis</strong> with a luxurious, fluid user interface, we bring the future of skincare shopping to your fingertips.
  </p>

</div>

---


## ✨ Features Summary

| Feature Category      | Key Capabilities                                                                                                                                                                                    |
| :-------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **🤖 Smart Tech**     | • **Skin Analyzer**: Interactive quiz for personalized product matching.<br>• **Smart Recommendations**: Algorithm-based suggestions.                                                               |
| **🔐 Authentication** | • **Secure Login**: JWT & Bcrypt protection.<br>• **Social Auth**: Google OAuth integration.<br>• **Recovery**: OTP-based password reset flow.                                                      |
| **🛍️ Shopping**       | • **Dynamic Cart**: Real-time updates & calculations.<br>• **Global Search**: Animated, centralized product search.<br>• **Payments**: Stripe & Razorpay integration.                               |
| **🎨 UI/UX**          | • **Premium Design**: Glassmorphism, magnetic buttons, & fluid animations.<br>• **Responsive**: Optimized for all devices via Tailwind CSS v4.<br>• **Dock Navigation**: macOS-style floating menu. |
| **🛠️ Admin**          | • **Dashboard**: Analytics & sales overview.<br>• **Product Management**: Create, update, delete products.<br>• **Customer Service**: Message center for inquiries.                                 |

---


## 📂 Project Structure

A quick look at the top-level directory structure:

```
Kumar-Kosmetics/
├── backend/                # Express.js Server & API
│   ├── controllers/        # Request handlers
│   ├── models/             # Mongoose schemas
│   ├── routes/             # API route definitions
│   ├── middleware/         # Auth & error handling
│   ├── lib/                # Database & service connections
│   └── server.js           # Entry point
│
├── frontend/               # React Application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Full page views
│   │   ├── store/          # Zustand state management
│   │   ├── hooks/          # Custom React hooks
│   │   ├── lib/            # Utilities & helpers
│   │   ├── assets/         # Images & static files
│   │   └── App.jsx         # Main application component
│   └── package.json
│
└── README.md
```

---

## 🛠️ Tech Stack

We use the cutting-edge **MERN Stack** supercharged with modern tooling.

| Domain       | Technology             | Purpose                                |
| :----------- | :--------------------- | :------------------------------------- |
| **Frontend** | **React 18 + Vite**    | Blazing fast UI rendering              |
|              | **Tailwind CSS v4**    | Next-gen utility-first styling         |
|              | **Framer Motion**      | Complex layout animations              |
|              | **Zustand**            | Lightweight, scalable state management |
|              | **Radix UI**           | Accessible, unstyled UI primitives     |
| **Backend**  | **Node.js + Express**  | Robust, scalable server architecture   |
|              | **MongoDB + Mongoose** | Flexible, document-based data storage  |
|              | **Redis**              | High-performance caching               |
|              | **Cloudinary**         | Optimized media management & delivery  |

---

## 🚀 Getting Started

Ready to deploy **Kumar Kosmetics**? Follow these steps.

### 1️⃣ Prerequisites

- **Node.js** (v16+)
- **MongoDB** (Local or Atlas)
- **Redis** (Optional, for speed boost)

### 2️⃣ Installation

```bash
# Clone the repository
git clone https://github.com/your-username/kumar-kosmetics.git
cd Kumar-Kosmetics

# 📦 Backend Setup
cd backend
npm install
# Create your .env file here
npm run dev

# 🎨 Frontend Setup (New Terminal)
cd ../frontend
npm install
npm run dev
```

### 3️⃣ Environment Variables

Create a `.env` file in `backend/` with the following:

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
STRIPE_SECRET_KEY=your_stripe_key
EMAIL_USER=your_email
EMAIL_PASS=your_password
GOOGLE_CLIENT_ID=your_google_id
GOOGLE_CLIENT_SECRET=your_google_secret
```

---

## 🤝 Contributing

We welcome contributions to make **Kumar Kosmetics** even better!

1.  **Fork the Project**
2.  **Create your Feature Branch** (`git checkout -b feature/AmazingFeature`)
3.  **Commit your Changes** (`git commit -m 'Add some AmazingFeature'`)
4.  **Push to the Branch** (`git push origin feature/AmazingFeature`)
5.  **Open a Pull Request**

---

## 📄 License

Distributed under the **ISC License**. See `LICENSE` for more information.

---

<div align="center">

### 🤝 Join the Revolution

Built by [Keshav Chauhan](https://keshavchauhan.in)

[Report Bug](https://github.com/your-username/kumar-kosmetics/issues) • [Request Feature](https://github.com/your-username/kumar-kosmetics/issues)

</div>
