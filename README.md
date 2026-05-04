# 🏛️ Tiles Gallery

> A premium tile showcase platform for discovering extraordinary ceramic, marble, terracotta, zellige, and artisan tiles from around the world.

## 🌐 Live URL

**[https://tiles-gallery.vercel.app](https://tiles-gallery.vercel.app)**

---

## 📖 Project Purpose

Tiles Gallery is a full-stack Next.js web application that serves as a curated tile discovery platform. Users can browse an extensive collection of premium tiles from global artisans, view detailed specifications, and manage their profiles — all within an elegantly designed, fully responsive interface.

---

## ✨ Key Features

- **Hero Banner** — "Discover Your Perfect Aesthetic" with animated tile mosaic background
- **Marquee** — Smooth scrolling ticker for new arrivals and featured collections
- **Featured Tiles** — Top 4 editor-picked tiles fetched from API
- **Gallery with Live Search** — Real-time filtering by name, material, or category
- **Tile Detail Page** — Large preview, specs, tags, creator info, and related tiles (private route)
- **Email/Password Auth** — Full registration and login with validation and toast feedback
- **Google OAuth** — One-click social login
- **My Profile Page** — Account info display with member since date
- **Update Profile** — Edit name and photo URL with live preview
- **Loading Skeletons** — Shimmer animations during data fetch
- **Custom 404 Page** — On-brand tile mosaic not-found page
- **Route Protection** — Middleware redirects unauthenticated users
- **Fully Responsive** — Mobile, tablet, and desktop optimised

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | Next.js 15 (App Router) |
| Language | TypeScript |
| Styling | Tailwind CSS + DaisyUI |
| Authentication | BetterAuth |
| Database | MongoDB (via MongoDB Atlas) |
| Animations | Animate.css |
| Marquee | react-fast-marquee |
| Toasts | react-hot-toast |
| Hosting | Vercel |

---

## 📦 NPM Packages Used

| Package | Purpose |
|---|---|
| `better-auth` | Authentication with MongoDB adapter and Google OAuth |
| `mongoose` | MongoDB object modelling |
| `mongodb` | MongoDB Node.js driver (BetterAuth adapter) |
| `daisyui` | Tailwind CSS component library |
| `react-hot-toast` | Lightweight toast notification system |
| `react-fast-marquee` | Smooth CSS-powered scrolling marquee |
| `animate.css` | Cross-browser CSS animation library (Challenge requirement) |

---

