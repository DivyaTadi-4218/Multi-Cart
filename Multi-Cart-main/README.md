# 🛒 Multi-Cart — AI-Powered Multi-Vendor E-Commerce Platform

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-001E2B?style=for-the-badge&logo=mongodb&logoColor=green)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=for-the-badge&logo=stripe&logoColor=white)
![Auth.js](https://img.shields.io/badge/Auth.js-000000?style=for-the-badge&logo=auth0&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer%20Motion-black?style=for-the-badge&logo=framer&logoColor=blue)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![AI](https://img.shields.io/badge/AI-Gemini-blueviolet?style=for-the-badge)

---

## 🚀 Overview

**Multi-Cart** is an AI-powered full-stack multi-vendor e-commerce platform built using **Next.js App Router**.  
It enables multiple vendors to manage products, orders, and earnings while providing customers with a smooth shopping experience enhanced by **AI chat support**, secure payments, and modern UI animations.

---

## ✨ Key Features

- 🤖 AI Chat Support for Customers (Gemini)
- 🏪 Multi-Vendor Marketplace System
- 🧑‍💼 Admin Panel & Vendor Dashboard
- 💳 Stripe Payment Integration
- 🔐 Authentication using Auth.js (NextAuth)
- 🎬 Smooth Animations with Framer Motion
- ☁️ Deployment using Vercel

---

## 🛠 Tech Stack

- Next.js (App Router)
- MongoDB
- Auth.js (NextAuth)
- Stripe
- Framer Motion
- AI Integration (Gemini)
- Cloudinary
- Nodemailer (Gmail SMTP)

---

## 📂 Project Structure

```
Multi-Cart/
├── app/
├── components/
├── lib/
├── models/
├── actions/
├── public/
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/Alisha-21-cloud/Multi-Cart.git
cd Multi-Cart
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Environment Variables

Create a `.env.local` file in the root directory:

```env
MONGODB_URL= // add your mongo db url
AUTH_SECRET="fkfoet3454sta0d52M2W5S"

GOOGLE_CLIENT_ID= // add your GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET= // add your GOOGLE_CLIENT_SECRET

CLOUDINARY_CLOUD_NAME= // add your CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_KEY= // add your CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET= // add your CLOUDINARY_API_SECRET

STRIPE_SECRET_KEY= // add your STRIPE_SECRET_KEY
STRIPE_WEBHOOK_SECRET= // add your STRIPE_WEBHOOK_SECRET

NEXT_BASE_URL="http://localhost:3000"

GMAIL_USER= // add your email
GMAIL_APP_PASSWORD= // add your app password

GEMINI_API_KEY= // add your gemini api key
```

---

### 4. Run the Development Server

```bash
npm run dev
```

Visit **http://localhost:3000**

---

## 🧪 Stripe Test Card

```
4242 4242 4242 4242
```

---

## ☁️ Deployment

Deploy easily using **Vercel**.  
Add all environment variables in the Vercel dashboard.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).


---

## 🙌 Author

**Divya Tadi**  
AI & Full-Stack Developer
