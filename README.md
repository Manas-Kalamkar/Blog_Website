# 📝 MKBlog – Professional Blog Application

This repository contains my solution for the **CA Monk Frontend Internship – Blog Application Website**. I elevated the project requirements by migrating the initial local JSON Server to a **live Cloud Backend (Supabase)**, creating a fully functional, deployable full-stack experience.

## 🚀 Live Demo: [https://manas-kalamkar.github.io/mkblog/](https://manas-kalamkar.github.io/mkblog/)


## 📷 Screenshots
<img width="1920" height="1080" alt="Screenshot from 2026-02-01 00-35-01" src="https://github.com/user-attachments/assets/1e1188db-3f51-4a7d-981b-9531fd3e2f93" />
<img width="1920" height="1080" alt="Screenshot from 2026-02-01 00-35-15" src="https://github.com/user-attachments/assets/9526a8f0-e0f2-462a-b021-933c452a3153" />
<img width="410" height="883" alt="Screenshot from 2026-02-01 00-35-48" src="https://github.com/user-attachments/assets/a71f04ef-db32-4c45-94d1-35e005aea35b" />
<img width="410" height="883" alt="Screenshot from 2026-02-01 00-36-00" src="https://github.com/user-attachments/assets/b8026088-7003-4846-a1b1-822e2a6adc86" />


---

## 🚀 Tech Stack

* **React + TypeScript** – Core frontend framework
* **Supabase** – PostgreSQL Cloud Database & API layer
* **TanStack Query (v5)** – Advanced server-state management & caching
* **Tailwind CSS** – Utility-first styling
* **shadcn/ui** – Accessible and reusable UI components
* **Vite** – Modern build tool for high-performance development

---

## ✨ Features Implemented

* 📄 **Dynamic Data Fetching**: Real-time retrieval of blog posts from a remote PostgreSQL database.
* 🔍 **Single Blog View**: Deep-linking and fetching specific articles by unique identifiers.
* ➕ **Cloud Persistence**: Ability to publish new blog posts directly to the cloud via a custom creation form.
* 🔄 **Smart Invalidation**: Automatic UI synchronization using TanStack Query mutations.
* ⏳ **Loading & Error States**: Comprehensive UI feedback using skeletons and error boundaries.
* 📱 **Responsive UI**: A fluid, mobile-first design built with Tailwind.

---

## 📂 Project Structure

```text
src/
│── api/               # Supabase client and API service functions
│── components/        # Reusable UI components (shadcn/ui + custom)
│── hooks/             # Custom TanStack Query hooks (useBlogs, useBlog)
│── types/             # TypeScript interfaces for database schema
│── lib/               # Utility functions (cn, etc.)
│── App.tsx            # Main application logic
└── main.tsx           # Entry point with QueryClientProvider
