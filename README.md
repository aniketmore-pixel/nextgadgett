# NextGadget

A full-stack **electronic gadgets E-Commerce platform** built with **React, Firebase, Redux
Toolkit, Express, Stripe, and TailwindCSS/DaisyUI**.\
It includes both a **web app** and a **Flutter mobile app**, supporting
features like authentication, cart, product management, order tracking,
admin dashboard, and secure payments.

------------------------------------------------------------------------

## 🚀 Features

### User Side

-   🔐 Authentication (Login, Register, Reset Password)
-   🛍 Browse Products (with categories & filters)
-   🔎 Product Search with Filtering
-   🛒 Cart Management (add, update, remove)
-   📦 Checkout Flow with Address & Payment
-   📜 Order History & Order Details
-   ⭐ Product Reviews
-   Responsive UI with TailwindCSS + DaisyUI

### Admin Side

-   📊 Admin Dashboard with Analytics
-   ➕ Add, Edit, Delete Products
-   🗑 Product Image Deletion (Firebase Storage)
-   📦 Manage Orders & Update Status
-   📈 Order Status Chart (Chart.js)
-   🔍 Product Search & Filtering in Admin Panel
-   👮 Admin-Only Protected Routes

### Tech Stack

-   **Frontend:** React, Redux Toolkit, React Router, TailwindCSS,
    DaisyUI
-   **Backend:** Express.js, Stripe API, Firebase
-   **Database & Storage:** Firebase Firestore & Firebase Storage
-   **Authentication:** Firebase Auth
-   **State Management:** Redux Toolkit
-   **Charts & Analytics:** Chart.js + React ChartJS-2
-   **Image Optimization:** react-lazy-load-image-component
-   **Mobile App:** Flutter (for Android/iOS integration)

------------------------------------------------------------------------

## 📂 Project Structure

    react-firebase-ecom/
    │── src/
    │   ├── components/        # UI Components (auth, cart, checkout, products, etc.)
    │   ├── pages/             # Page-level components (home, cart, orders, admin, etc.)
    │   ├── redux/             # Redux slices & store
    │   ├── firebase/          # Firebase configuration
    │   ├── hooks/             # Custom React hooks
    │   ├── utils/             # Helper utilities (e.g. formatPrice)
    │── server.js              # Express + Stripe backend server
    │── package.json           # Project dependencies & scripts
    │── README.md              # Documentation
    │── flutter_app/           # Flutter mobile app (cross-platform)

------------------------------------------------------------------------

## ⚡ Getting Started

### 1️⃣ Clone the repository

``` bash
git clone https://github.com/yourusername/react-firebase-ecom.git
cd react-firebase-ecom
```

### 2️⃣ Install dependencies

``` bash
npm install
```

### 3️⃣ Setup Firebase

-   Create a Firebase project in the [Firebase
    Console](https://console.firebase.google.com/)
-   Enable **Authentication, Firestore, and Storage**
-   Copy your Firebase credentials into `.env`

```{=html}
<!-- -->
```
    VITE_API_KEY=your_api_key
    VITE_AUTH_DOMAIN=your_auth_domain
    VITE_PROJECT_ID=your_project_id
    VITE_STORAGE_BUCKET=your_storage_bucket
    VITE_MESSAGING_SENDER_ID=your_messaging_sender_id
    VITE_APP_ID=your_app_id
    VITE_ADMIN_KEY=your_admin_email
    STRIPE_SECRET_KEY=your_stripe_secret_key

### 4️⃣ Run the development server

``` bash
npm run dev
```

### 5️⃣ Run the backend server (Stripe payments)

``` bash
npm run server
```

### 6️⃣ Build for production

``` bash
npm run build
```

------------------------------------------------------------------------

## 📱 Flutter App

This repo also includes a **Flutter app** that connects to the same
Firebase backend.\
It supports: - 🔐 User Authentication - 🛍 Product Browsing - 🛒 Cart &
Checkout - 📦 Order Tracking

To run the Flutter app:

``` bash
cd flutter_app
flutter pub get
flutter run
```

------------------------------------------------------------------------

## 📊 Admin Dashboard

-   Access the **Admin Panel** via `yourapp.com/admin`
-   Only the email set in `.env` as `VITE_ADMIN_KEY` can access admin
    features.

------------------------------------------------------------------------

## 🔑 Scripts

  Command             Description
  ------------------- ------------------------------
  `npm run dev`       Run Vite development server
  `npm run build`     Build production app
  `npm run preview`   Preview production build
  `npm run server`    Run Express + Stripe backend
  `npm start`         Start backend in production

------------------------------------------------------------------------

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!\
Feel free to fork this repo and submit pull requests.

------------------------------------------------------------------------

## 📜 License

This project is licensed under the **MIT License**.

------------------------------------------------------------------------

### ⭐ If you like this project, give it a star on GitHub!
