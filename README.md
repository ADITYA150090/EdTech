<<<<<<< HEAD
# 📚 EdTech Frontend — Next.js Application

Modern, scalable frontend architecture for an EdTech platform (Courses + Blog) built with **Next.js App Router**, **React**, and **Tailwind CSS**.

---

## 🚀 Tech Stack

* ⚛️ Next.js (App Router)
* ⚛️ React
* 🎨 Tailwind CSS
* 🔐 JWT Authentication
* 🌐 REST APIs (Microservices Backend)
* 🧠 TypeScript (recommended)

---

## 🏗️ Project Structure

```
src/
│
├── app/                # Next.js App Router (pages, layouts, routing)
│   ├── layout.tsx      # Root layout
│   ├── page.tsx        # Home page
│   │
│   ├── courses/        # Course-related routes
│   │   ├── page.tsx
│   │   └── [id]/page.tsx
│   │
│   ├── blog/           # Blog routes
│   │   ├── page.tsx
│   │   └── [slug]/page.tsx
│   │
│   ├── dashboard/      # User dashboard
│   │   ├── layout.tsx
│   │   └── page.tsx
│   │
│   └── auth/           # Authentication pages
│       ├── login/page.tsx
│       └── register/page.tsx
│
├── components/         # Reusable UI components
│   ├── ui/             # Generic components (Button, Input, Modal)
│   ├── layout/         # Navbar, Footer, Sidebar
│   └── course/         # Course-specific components
│
├── features/           # Feature-based modules (domain-driven)
│   ├── auth/
│   ├── courses/
│   └── blog/
│
├── services/           # API communication layer
│   ├── apiClient.ts    # Axios / Fetch instance
│   ├── authApi.ts
│   ├── courseApi.ts
│   └── blogApi.ts
│
├── hooks/              # Custom React hooks
│   ├── useAuth.ts
│   ├── useDebounce.ts
│   └── usePagination.ts
│
├── context/            # Global state providers
│   ├── AuthContext.tsx
│   └── ThemeContext.tsx
│
├── lib/                # Utilities and helpers
│   ├── utils.ts
│   ├── validators.ts
│   └── authHelpers.ts
│
├── types/              # TypeScript types/interfaces
│   ├── user.ts
│   ├── course.ts
│   └── blog.ts
│
├── styles/             # Global styles
│   └── globals.css
│
├── assets/             # Static assets
│   ├── images/
│   ├── icons/
│   └── fonts/
│
└── constants/          # Application-wide constants
    └── index.ts
```

---

## 🧠 Architecture Principles

### ✅ App Router First

Uses Next.js modern routing system with layouts and server components.

### ✅ Feature-Based Design

Code organized by business domains (auth, courses, blog).

### ✅ Separation of Concerns

* UI components
* Business logic
* API layer
* State management
* Utilities

### ✅ Scalable Structure

Designed to grow from a student project to a production system.

---

## 🌐 API Integration

Frontend communicates with backend microservices via an API Gateway:

```
Browser → Next.js App → API Gateway → Microservices
```

Authentication handled using JWT tokens.

---

## 🏁 Getting Started

### Install dependencies

```
npm install
```

### Run development server

```
npm run dev
```

Open http://localhost:3000 in your browser.

---

## 📌 Future Enhancements

* 🔍 Search functionality
* 💬 Real-time features (WebSockets)
* 🎬 Video streaming integration
* 🌙 Dark mode support
* 📱 PWA support

---

## 👨‍💻 Author

Built as a scalable frontend for a modern EdTech platform.

---

⭐ If you find this project helpful, consider giving it a star!
=======
# EdTech
This is Initiation of blog and Edtech technology , i am workin on this with one of my friend to document everything that i have learnd in past years
>>>>>>> 071cdf03a6bf1f00589eb1e61369dff47cf40887
