#  RideCo — Real-Time Ride Sharing System

A frontend web application for a real-time ride-sharing platform built with plain HTML, CSS, and JavaScript — no frameworks, no build tools. Designed with a 3-role system for Passengers, Drivers, and Admins, and structured for easy backend integration.

> ⚠️ **Note:** This is a frontend-only project currently. Backend integration is in progress.

---

## ✨ Features

- 🧑‍💼 **Passenger Portal** — Register, request rides, track in real-time, make payments, view history, and rate drivers
- 🚘 **Driver Portal** — Accept/decline ride requests, manage active rides, and view earnings
- 🛠️ **Admin Panel** — Monitor live rides, manage drivers, and generate reports
- 📡 **Backend-Ready Architecture** — API layer pre-written and ready to connect
- 🔧 **Backend In Progress** — Currently working on backend integration
- 🎨 **3-Layer CSS System** — Organized, scalable styling across all pages

---

## 🧠 Tech Stack

- **HTML** — Page structure
- **CSS** — Styling with a 3-layer system
- **JavaScript** — Navigation, UI interactions, mock data, and API layer

---

## 👥 User Roles

| Role | Pages |
|------|-------|
| Passenger | Login, Register, Dashboard, Request Ride, Track Ride, Payment, History, Rating |
| Driver | Login, Dashboard, Ride Request, Active Ride, Earnings |
| Admin | Login, Dashboard, Drivers, Rides, Reports |

---
```

## 📁 Project Structure
rideco/
├── index.html                  ← Landing page
├── assets/
│   └── css/
│       ├── base.css            ← Shared styles (every page)
│       ├── layouts.css         ← Shared layouts
│       ├── passenger/          ← Passenger page styles
│       ├── driver/             ← Driver page styles
│       └── admin/              ← Admin page styles
├── js/
│   ├── nav.js                  ← Navigation
│   ├── data.js                 ← Mock data
│   ├── ui.js                   ← UI interactions
│   └── api.js                  ← API calls (backend-ready)
├── data/
│   ├── rides.json
│   ├── drivers.json
│   └── users.json
└── pages/
├── passenger/
├── driver/
└── admin/
```
---

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/Huria-Tariq/RideCo-RealTimeRideSharingSystem.git
```
2. Open `index.html` in your browser — no server needed!

---

## 👥 Team Members

- **Huria Tariq** — [GitHub Profile](https://github.com/Huria-Tariq)
- **Malyka Khan** — [GitHub Profile](https://github.com/MalykaZaheerKhan)

---

