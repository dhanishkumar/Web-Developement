<h1 align="center">🛍️ Rajput Shoping</h1>

<p align="center">
  <img src="https://img.shields.io/badge/React-18-blue?style=flat&logo=react" />
  <img src="https://img.shields.io/badge/Firebase-Auth,DB,Storage-orange?style=flat&logo=firebase" />
  <img src="https://img.shields.io/badge/Deployed-Firebase%20Hosting-brightgreen?style=flat&logo=firebase" />
</p>

<p align="center">
  <b>A modern and animated e-commerce site built with React, Firebase, and Tailwind CSS</b><br>
  <i>Fully responsive UI | Admin dashboard | Realtime database | QR Payment</i>
</p>

---

## ✨ Features

- 🔐 **User Authentication** (Signup/Login with Email or Google)
- 🛒 **Add to Cart & Checkout** Functionality
- 🛍️ **Admin Dashboard** for Managing Products
- 📦 **Dynamic Product Listing** from Firestore
- 📱 **Fully Responsive Design**
- 💳 **QR Code Based Payment System**
- ☁️ **Realtime Firestore Database**
- 🎞️ **Smooth Page Transitions with Framer Motion**

---

## 🚀 Tech Stack

| Frontend       | Backend/Services       | Database       | Styling         | Deployment         |
|----------------|------------------------|----------------|------------------|--------------------|
| React, React Router | Firebase Auth, Functions | Firestore DB    | Tailwind CSS     | Firebase Hosting    |
| Lazy Loading   | Firebase Storage       | Cloud Storage  | Framer Motion (FX) |                    |

---

## 📂 Project Structure (Simplified)

```
Rajput-Shoping/
├── src/
│   ├── components/       # Reusable components (Header, Spinner, etc.)
│   ├── pages/            # Page components
│   ├── context/          # Auth and Cart Context
│   ├── config/           # Firebase config
│   ├── assets/           # Images and static files
│   └── App.jsx           # Main application with routes
```

---

## 🔧 Getting Started

```bash
git clone https://github.com/your-username/Rajput-Shoping.git
cd Rajput-Shoping
npm install
npm run dev
```

---

## 🔑 Firebase Setup

1. Go to [Firebase Console](https://console.firebase.google.com/)
2. Create a new project
3. Enable the following:
   - Firebase Authentication (Email/Password + Google)
   - Firestore Database
   - Firebase Storage
4. Replace Firebase config in:

```js
// src/config/firebase.js
const firebaseConfig = {
  apiKey: "...",
  authDomain: "...",
  projectId: "...",
  storageBucket: "...",
  messagingSenderId: "...",
  appId: "..."
}
```

---

## 👨‍💻 Developer

**Dhanish Kumar**  
🎓 B.Tech CSE (2025), Galgotias University  
🔗 [LinkedIn](https://linkedin.com/in/dhanish-kumar-533aaa173)  
🐙 [GitHub](https://github.com/dhanishkumar)

---

## 💬 Feedback or Collaboration?

📧 Reach out at: **dhanishkumar2001@gmail.com**

---

> Made with ❤️ using React + Firebase
