# 📊 Sales Team Dashboard

A full-stack web application for managing sales deals, built with modern web technologies. This dashboard allows sales representatives to create and track deals while enforcing secure, role-based access using Supabase Row Level Security (RLS).

---

## 🚀 Features

### 🔐 Authentication
- User signup & login (Supabase Auth)
- Session management
- Protected routes

### 👤 Role-Based Access
- Only users with `account_type = 'rep'` can create deals
- Enforced at **database level (RLS policies)**

### 💼 Deal Management
- Create new sales deals
- Associate deals with the logged-in user
- View user-specific data

### 🛡️ Security
- Row Level Security (RLS) policies
- JWT-based authentication
- Backend enforced authorization (not just frontend)

---

## 🧱 Tech Stack

### Frontend
- Next.js (App Router)
- React

### Backend / BaaS
- Supabase
  - PostgreSQL (Database)
  - Supabase Auth (JWT-based authentication)
  - Row Level Security (RLS)

---

## 📁 Project Structure
