# JC Summit — LiveCards 🚀

A premium, real-time question display system developed for **ACM MUJ** events. Built with a focus on high-agency design, cinematic animations, and instant WebSocket synchronization.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

---

## ✨ Features

- 💎 **Premium Aesthetic**: Dark mode, Apple Music-inspired glassmorphism, and abstract animated backgrounds.
- ⚡ **Real-Time Synchronisation**: Instant question broadcasting via custom WebSocket implementation.
- 🔒 **Secure Admin Panel**: Password-protected dashboard for clear-board, question deletion, and live moderation.
- 🌪️ **Cinematic UI**: Text scrambling, spring physics card animations, and liquid-glass borders (powered by Framer Motion).
- 🗄️ **Supabase Integration**: Permanent data persistence using PostgreSQL with ultra-low latency response times.

---

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 16 (App Router)
- **Styling**: Tailwind CSS + Vanilla CSS (Variables)
- **Animations**: Framer Motion
- **Communication**: Custom `useWebSocket` hook with auto-reconnect

### Backend
- **Engine**: Node.js & Express
- **Real-time**: `ws` (WebSocket)
- **Database**: Supabase (PostgreSQL)
- **Security**: Secret-key based authentication middleware

---

## 🚀 Getting Started

### Prerequisites
- Node.js 18+
- Supabase Project (URL & Service Role Key)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Ronitdoes/jc-summit-26.git
   cd jc-summit-26
   ```

2. **Frontend Setup**
   ```bash
   cd frontend
   npm install
   # Create a .env.local with:
   # NEXT_PUBLIC_WS_URL=ws://localhost:4000
   # NEXT_PUBLIC_API_URL=http://localhost:4000
   # NEXT_PUBLIC_ADMIN_SECRET=your_admin_secret
   # NEXT_PUBLIC_DEFAULT_SESSION_ID=your_session_uuid
   npm run dev
   ```

3. **Backend Setup**
   ```bash
   cd ../backend
   npm install
   # Create a .env with:
   # PORT=4000
   # SUPABASE_URL=your_supabase_url
   # SUPABASE_SERVICE_ROLE_KEY=your_service_role_key
   # ADMIN_SECRET=your_admin_secret
   # CLIENT_ORIGIN=http://localhost:3000
   npm run dev
   ```

---


## 🏆 Credits

Developed by **ACM Student Chapter — Manipal University Jaipur**.
