# 🛡️ Mini SOC

> **A lightweight Personal Threat Intelligence Dashboard.**
> "Monitor, analyze, and report threats in real-time."

[![NestJS](https://img.shields.io/badge/Backend-NestJS-%23E0234E)](https://nestjs.com/)
[![React](https://img.shields.io/badge/Frontend-React-%2361DAFB)](https://react.dev/)
[![Supabase](https://img.shields.io/badge/Database-Supabase-3ecf8e)](https://supabase.com/)

## ✨ Features
- **Community Threat Reports:** Submit suspicious IPs, domains, and phishing attempts.
- **Security Dashboard:** High-level overview of total, critical, and pending threats.
- **Admin Management:** Role-based access to review, resolve, or delete reports.
- **Validation & Security:** Strict DTO validation, rate limiting, and Helmet integration.

## 🛠️ Tech Stack
- **React (Vite):** Fast, modern frontend architecture.
- **Tailwind CSS:** Utility-first styling for a clean SOC interface.
- **NestJS:** Scalable REST API with structured DTOs and exception filters.
- **Supabase:** PostgreSQL database with Row Level Security (RLS) and Auth.

## 🚀 Getting Started

1. `git clone https://github.com/your-username/mini-soc.git`
2. **Backend Setup:**
   - `cd backend && npm install`
   - Configure `.env` with `SUPABASE_URL` and `SUPABASE_KEY`.
   - `npm run start:dev`
3. **Frontend Setup:**
   - `cd frontend && npm install`
   - `npm run dev`

---

Would you like me to generate the **SQL Schema** script for the `threat_reports` table so you can set up the Supabase database instantly?
