# 🚗 Skrotbil Platform (Full-Stack Web Application)

🔗 **Live Demo:** https://skrotbil-site.vercel.app  

---

## 📌 Overview

This project is a **production-ready full-stack web application** built to streamline the process of selling scrap cars.

The platform allows users to:
- Submit vehicle details
- Receive offers
- Complete the selling process through a guided, user-friendly flow

The focus has been on:
- **High-conversion UX**
- **Clean architecture**
- **Scalable backend integration**

---

## ⚙️ Tech Stack

**Frontend**
- Next.js (App Router)
- TypeScript
- Tailwind CSS

**Backend**
- Supabase (Database, Storage, Edge Functions)
- API Routes (Next.js)

**Other**
- Resend (email handling)
- External vehicle lookup API

---

## 🧠 Key Features

### 🚀 Lead Flow System
- Multi-step form (custom built)
- Intelligent validation
- Manual + automatic vehicle input
- Optimized for conversion

### 📸 Image Upload
- Upload multiple images
- Integrated with Supabase Storage

### 📩 Offer Handling
- Structured backend flow for:
  - Lead submission
  - Offer creation
  - Customer acceptance flow

### 🔄 Post-Acceptance Flow
- Dynamic user paths depending on scenario:
  - Pickup
  - Customer delivery
- Clean and minimal UX (non-overwhelming)

### 🧩 Modular Architecture
- Reusable components
- Separation of concerns:
  - `components/`
  - `hooks/`
  - `services/`
  - `lib/`

---

## 🏗️ Architecture Highlights

- Custom hooks for business logic (`useLeadFlow`, `useLeadForm`)
- Clean separation between UI and logic
- Scalable folder structure
- API abstraction layer for maintainability

---

## 📊 Real-World Focus

This is **not just a demo project**.

It is designed as a **real business platform** with:
- Conversion-focused UI
- Backend-ready structure
- Scalable architecture for future growth

---



---
